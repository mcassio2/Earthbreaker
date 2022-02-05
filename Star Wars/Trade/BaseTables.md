# Base Trade Tables

**Trade Goods Types**

| Name             | Base Price | Unit   |
|------------------|------------|--------|
| Food             | 20         | CR/ton |
| Industrial Goods | 80         | CR/ton |
| Minerals         | 15         | CR/ton |
| Chemicals        | 20         | CR/ton |
| Luxury Goods     | 250        | CR/ton |
| Contraband       | 1250       | CR/ton |
| Tabanna Gas      | 500        | CR/ton |


**Quality Grades**

| Name          | Price Modifier | Availability Probability |
|---------------|----------------|--------------------------|
| Poor          | / 2            | 20                       |
| Common        | * 1            | 55                       |
| Good          | * 2            | 20                       |
| Exceptional   | * 4            | 5                        |


**Planet Types**

| Name         | Modifiers                                                       |
|--------------|-----------------------------------------------------------------|
| Agricultural | (Food)/4, (Industrial Goods)*2                                  |
| Industrial   | (Industrial Goods)/4, (Food)*2, (Minerals)*4, (Chemicals)*4     |
| Commercial   | (Food)*2, (Luxury Goods)/2, (Contraband)*2                      |
| Military     | (Food)*3, (Industrial Goods)*2                                  |
| Specialty    | (Luxury Goods)/2                                                |
| Criminal     | (Contraband)/8, (Industrial Goods)*2, (Food)*2                  |
| Government   | (Food)*2, (Industrial Goods)*2, (Luxury Goods)*6                |
| Mining       | (Food)*2, (Industrial Goods)*2, (Minerals)/8                    |
| Refinery     | (Food)*2, (Industrial Goods)*2, (Chemicals)/8                   |
