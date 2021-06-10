# Antwoorden

1. Copy paste je gemaakte SQL query hieronder
   SELECT name,platform,genre FROM game, publisher, platform, genre WHERE game.name LIKE 'b%'
2. Copy paste je gemaakte SQL query hieronder
    SELECT name,platform,publisher FROM game, publisher, platform, genre WHERE game.year LIKE '%2013%'
3. Copy paste je gemaakte SQL query hieronder
    SELECT name, genre, year, global_sales FROM game, publisher, platform, genre WHERE game.year LIKE '%2000%'
4. Copy paste je gemaakte SQL query hieronder
    SELECT genre, publisher, year, jp_sales FROM game,genre,platform,publisher WHERE game.name LIKE 'a%0'
5. Copy paste je gemaakte SQL query hieronder
   SELECT name, genre, publisher, year FROM game, genre, publisher, platform WHERE platform.platform LIKE '%PC%'