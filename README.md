# Query-Test
-- Select all columns from the Movies table
SELECT *
FROM Movies

-- Order the results by AverageRating in descending order (highest rated first)
ORDER BY AverageRating DESC,

-- If ratings are equal, use ReleaseYear as a secondary sort with ascending order (newer first)
ReleaseYear ASC;
