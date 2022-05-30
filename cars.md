# Car_Dealer

## Modello: Car

## table: Cars

- id:               BIGINT          PRIMARYKEY (NOTNULL, AUTOINCREMENTS, UNIQUE)
- name:             ARCHAR(209)     NOTNULL
- img:              VARCHAR(255)    NULL
- price:            DECIMAL (8,2)   NOTNULL
- motor:            VARCHAR(255)    NOTNULL
- traction:         VARCHAR(3)      NULL
- transmission      VARCHAR(9)      NOTNULL DEFAULT("manual")
- color:            VARCHAR(100)    NOTNULL DEFAULT("white")
- km:               FLOAT(8,2)      NULL
- available_in:     DATE            NULL
