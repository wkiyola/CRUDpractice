# CRUDpractice

1. INSERT two users:

              SELECT *
              FROM users
              WHERE id IN (501, 502);

UPDATE all Ohio addresses to "REDACTED":

                    UPDATE usersAddress
                    SET 
                      state = 'REDACTED'
                        WHERE
                        state = 'OH';


All three DELETES  DELETE from usersContact DELETE from usersAddress  DELETE from users

                DELETE FROM usersAddress
                WHERE 
                user_id = 114;
                DELETE FROM usersContact
                WHERE 
                user_id = 114;
                DELETE FROM users
                WHERE 
                id = 114;
