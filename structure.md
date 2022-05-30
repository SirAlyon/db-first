# Car Dealer

## Modello: Car

##Table: Cars

- id:               BIGINT NOTNULL INDEX
- targa:            CHAR(9) NULL UNIQUE (FW-675-VA) //Ammesso che il concessionario si trovi in Italia
- marca:            VARCHAR(30) NOTNULL
- modello:          VARCHAR(60) NULL
- versione:         VARCHAR(30) NULL
- carburante:       VARCHAR(50) NULL
- cilindrata:       SMALLINT NULL
- cavalli:          SMALLINT NULL
- km:               MEDIUMINT NULL
- carrozzeria:      VARCHAR(20) NULL
- anno:             YEAR NULL
- prezzo:           DECIMAL(9, 2) NOTNULL
- prezzo_speciale:  DECIMAL(9, 2) NULL
- cambio:           VARCHAR(15) NOTNULL
- n_porte:          CHAR(3) NOTNULL
- discount:         FLOAT(3,1) NULL
- n_proprietari:    TINYINT NULL
- n_posti:          TINYINT NOTNULL
- peso:             DECIMAL(5,2) NULL
- lunghezza:        DECIMAL(5,2) NULL
- altezza:          DECIMAL(5,2) NULL
- car_image:        VARCHAR(255) NULL
- in_stock:         TINYINT NOTNULL DEFAULT(0)
