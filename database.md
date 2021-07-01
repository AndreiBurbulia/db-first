# Database

## Struttura
## table name: cars

- Id                                BIGINT              PRIMARY KEY UNIQUE NOTNULL 
- Marca                             VARCHAR(30)         NOTNULL  INDEX
- Modello                           VARCHAR(50)         NOTNULL  INDEX
- Data Immatricolazione             DATE                NOTNULL
- Anno                              YEAR                NOTNULL  INDEX
- Prezzo                            DECIMAL(8, 2)       NOTNULL  INDEX
- Potenza Kw                        SMALLINT            NULL
- Cavalli                           SMALLINT            NULL
- Colore                            VARCHAR(30)         NOTNULL
- Carozzeria                        VARCHAR(30)         NULL
- Peso                              SMALLINT            NULL
- Trazione                          VARCHAR(30)         NOTNULL
- Classe Emissioni                  TINYINT             NULL
- Sicurezza                         TEXT                NULL
- Comfort                           TEXT                NULL
- Capienza Bagagliaio               SMALLINT            NULL
- Set pneumatici                    TEXT                NULL
- Km percorsi                       INT                 NOTNULL  INDEX
- Proprietari                       TINYINT             NULL
- Carburante                        VARCHAR(30)         NOTNULL  INDEX
- Cambio                            VARCHAR(30)         NOTNULL  INDEX
- N. di porte                       TINYINT             NULL
- Foto                              VARCHAR(255)        NULL
