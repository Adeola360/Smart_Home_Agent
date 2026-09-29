# Smart_Home_Agent
CREATE TABLE sensor_data (
    id INTEGER PRIMARY KEY,
    timestamp DATETIME NOT NULL,
    temperature FLOAT,
    motion_detected BOOLEAN,
    door_open BOOLEAN,
    window_open BOOLEAN,
    light_on BOOLEAN,
    tv_on BOOLEAN,
    energy_usage_kw FLOAT
);

CREATE TABLE agent_decisions (
    decision_id INTEGER PRIMARY KEY,
    sensor_id INTEGER NOT NULL,
    agent_name TEXT NOT NULL,
    decision TEXT NOT NULL,
    confidence FLOAT,
    timestamp DATETIME NOT NULL,
    FOREIGN KEY (sensor_id) REFERENCES sensor_data(id)
);

CREATE TABLE system_log (
    log_id INTEGER PRIMARY KEY,
    timestamp DATETIME NOT NULL,
    message TEXT NOT NULL,
    severity TEXT
);

CREATE TABLE device_state (
    id INTEGER PRIMARY KEY,
    last_updated DATETIME NOT NULL,
    heating_on BOOLEAN,
    cooling_on BOOLEAN,
    light_on BOOLEAN,
    tv_on BOOLEAN
);

CREATE TABLE anomalies (
    anomaly_id INTEGER PRIMARY KEY,
    sensor_id INTEGER NOT NULL,
    description TEXT NOT NULL,
    severity TEXT,
    timestamp DATETIME NOT NULL,
    FOREIGN KEY (sensor_id) REFERENCES sensor_data(id)
);
