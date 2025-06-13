# Spotify using Advanced SQL Data Analysis

<p align="left">
  <img src="spotify_logo.jpg" alt="Photo" width="800"/>
</p>

# Overview
This project focuses on data analysis using a Spotify dataset through SQL. It covers the complete process from normalizing a denormalized dataset to performing SQL queries of varying complexity and optimizing query performance. The primary objective is to extract actionable insights by applying advanced, practical SQL techniques in a real-world context.

```sql
-- create table
DROP TABLE IF EXISTS spotify;
CREATE TABLE spotify (
    artist VARCHAR(255),
    track VARCHAR(255),
    album VARCHAR(255),
    album_type VARCHAR(50),
    danceability FLOAT,
    energy FLOAT,
    loudness FLOAT,
    speechiness FLOAT,
    acousticness FLOAT,
    instrumentalness FLOAT,
    liveness FLOAT,
    valence FLOAT,
    tempo FLOAT,
    duration_min FLOAT,
    title VARCHAR(255),
    channel VARCHAR(255),
    views FLOAT,
    likes BIGINT,
    comments BIGINT,
    licensed BOOLEAN,
    official_video BOOLEAN,
    stream BIGINT,
    energy_liveness FLOAT,
    most_played_on VARCHAR(50)
);
```
# Project Steps
## 1. Data Exploration
Before diving into SQL, it's important to understand our dataset. Before continuing, our dataset contains columns such as:


