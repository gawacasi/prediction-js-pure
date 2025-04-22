CREATE TABLE predicoes (
    id SERIAL PRIMARY KEY,
    location VARCHAR(255),
    operator VARCHAR(255),
    aboard INTEGER,
    ground INTEGER,
    year INTEGER,
    month INTEGER,
    weekday INTEGER,
    aircraft_type VARCHAR(255),
    prediction INTEGER,
    input_chart_base64 TEXT,
    result_chart_base64 TEXT
);
