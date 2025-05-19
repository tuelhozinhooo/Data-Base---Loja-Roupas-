# Data-Base---Loja-Roupas-
Loja de roupas básica.


CREATE TABLE Roupas (
    ID INT KEY AUTO_INCREMENT,
    Tipo VARCHAR(50),
    Tamanho VARCHAR(5),
    Preco DECIMAL(10, 2),
    Quantidade INT
);

INSERT INTO Roupas (Tipo, Tamanho, Preco, Quantidade)
VALUES 
('Calça Jeans', 'G', 89.90, 5),
('Vestido', 'P', 119.90, 8),
('Camisa Social', 'M', 79.90, 4),
('Shorts', 'GG', 39.90, 12);



UPDATE Roupas
SET  Preco = 179.90, Quantidade = 20 WHERE ID = 3;


SELECT * FROM Roupas


