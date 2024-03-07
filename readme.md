| FIELD                 | TYPE        | ATTRIBUTES                        | INDEXES     |
| --------------------- | ----------- | --------------------------------- | ----------- |
| id                    | INT         | (NOT NULL, UNIQUE) AUTO_INCREMENT | PRIMARY_KEY |
| brand                 | VARCHAR(30) | NOT NULL                          |             |
| model                 | VARCHAR(50) | NOT NULL                          |             |
| engine_type           | VARCHAR(30) | NOT NULL                          |             |
| doors                 | TINYINT     | NOT NULL, UNSIGNED                |             |
| fuel_consumption      | TINYINT     | NULL, UNSIGNED                    |             |
| energy_consumption    | TINYINT     | NULL, UNSIGNED                    |             |
| transmission          | VARCHAR(3)  | NOT NULL                          |             |
| general_condition     | TINYINT(5)  | NOT NULL, UNSIGNED                |             |
| kilometer_count       | INT         | NOT NULL, UNSIGNED                |             |
| park                  | VARCHAR(4)  | NULL                              |             |
| auto_trader_appraisal | INT         | NULL                              |             |
| cost                  | INT         | NOT NULL                          |             |
| sale_price            | INT         | NOT NULL                          |             |
| vin_number            | CHAR(17)    | NOT NULL, UNIQUE                  |             |
| registration_plate    | CHAR(8)     | NOT NULL, UNIQUE                  |             |
| registration_date     | DATE        | NOT NULL                          |             |
