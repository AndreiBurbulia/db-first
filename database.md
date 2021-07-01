# Database

## Struttura
## table name: cars

- Id                                BIGINT              PRIMARY KEY UNIQUE NOTNULL AUTOINCREMENT
- Marca                             VARCHAR(30)         NOTNULL  INDEX
- Modello                           VARCHAR(50)         NOTNULL  INDEX
- Data Immatricolazione             DATE                NULL
- Targa                             VARCHAR(10)         NOTNULL
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
- Km percorsi                       MEDIUMINT           NOTNULL  INDEX
- Proprietari                       TINYINT             NULL
- Carburante                        VARCHAR(30)         NOTNULL  INDEX
- Cambio                            VARCHAR(30)         NOTNULL  INDEX
- N. di porte                       TINYINT             NULL
- Foto                              VARCHAR(255)        NULL
- Note                              TEXT                NULL
- Pubblicato                        TINYINT             NULL
- Data Creazione                    DATETIME            NULL
- Ultimo Aggiornamento              DATETIME            NULL