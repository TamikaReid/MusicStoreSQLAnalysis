# Digital Music Store Database SQL Queries

This repository contains SQL queries that retrieve valuable insights from the Digital Music Store Database. Each query is designed to provide specific information for decision-making and analysis within the context of a digital music store.

## Query 1: Album Track Length Aggregation

This SQL query retrieves information about albums and their aggregated track lengths. It combines data from the "Album" and "Track" tables, calculating the total duration of tracks in each album. The query groups the results by album title and ID, ordering them in descending order based on the total track length. This query provides a list of albums ranked by their combined track lengths.

## Query 2: Top Rock Music Artists

This SQL query identifies the top 10 artists who have written the most rock music tracks in the dataset. It leverages data from the "Artist," "Album," "Track," and "Genre" tables. By counting tracks authored by each artist within the rock genre, the query showcases the artists contributing the highest number of rock music tracks. This information is valuable for organizing rock music-focused events or promotions.

## Query 3: Invoice Distribution by Billing Country

This SQL query analyzes invoice distribution across different billing countries. It connects the "Invoice" and "Customer" tables, calculating metrics for each unique billing country, including the total number of invoices and distinct customers. The results are grouped by billing country, ordered by the total number of invoices in descending order. This query offers insights into invoice distribution among various countries and customer diversity contributing to these invoices.

## Query 4: Media Type Revenue Analysis

This SQL query analyzes revenue generation across various media types. It utilizes data from the `InvoiceLine`, `Track`, and `MediaType` tables to calculate total revenue for each media type. The query aggregates revenue figures for each type and arranges the results in descending order based on total revenue. This query helps assess the revenue contribution of different media types within the digital music store.
