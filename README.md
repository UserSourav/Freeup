CREATE DATABASE Freeup;


use Freeup;


CREATE TABLE Freeup (
    UID char,
    Name char,
    Email char
    
);


ALTER TABLE Freeup MODIFY Name VARCHAR(50);

ALTER TABLE Freeup MODIFY Email VARCHAR(50);

ALTER TABLE Freeup MODIFY UID INT(50);

INSERT INTO Freeup (UID, Name, Email) VALUES
    -> (1, 'sourav', 'ss6015@edu.in'),
    -> (2, 'arnav', 'aa6015@edu.in'),
    -> (3, 'kwaish', 'kw6015@edu.in'),
    -> (4, 'nandini', 'na6015@edu.in'),
    -> (5, 'manan', 'ma6015@edu.in'),
    -> (6, 'utsav', 'ut6015@edu.in'),
    -> (7, 'daksh', 'da6015@edu.in'),
    -> (8, 'shruti', 'sh6015@edu.in'),
    -> (9, 'rhizoo', 'rh6015@edu.in'),
    -> (10, 'arav', 'ar6015@edu.in');


    SELECT * FROM Freeup;
