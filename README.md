# 4.Sql
Pengerjaan 4 Dumbways.id

CREATE TABLE book_tb(
    id VARCHAR (20) NOT NULL,
    name VARCHAR (50) NOT NULL,
    category VARCHAR(100) NOT NULL,
    writer_id VARCHAR(100) NOT NULL,
    Publication_year DATETIME NOT NULL,
    img LONGBLOB NOT NULL,
    PRIMARY KEY (id)
);

CREATE TABLE category_tb (
    id VARCHAR (20) NOT NULL,
    name VARCHAR (50) NOT NULL,
    
    PRIMARY KEY (id)
);
