CREATE TABLE predicoes (
    id SERIAL PRIMARY KEY,
    location TEXT,
    operator TEXT,
    aboard INTEGER,
    ground INTEGER,
    year INTEGER,
    month INTEGER,
    weekday TEXT,
    aircraft_type TEXT,
    prediction INTEGER,
    input_chart_base64 TEXT,
    result_chart_base64 TEXT,
    aboard_histogram_base64 TEXT,
    fatal_pie_base64 TEXT
);
