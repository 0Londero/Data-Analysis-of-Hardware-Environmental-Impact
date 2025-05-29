#### Objective



| Variable                  | Type         | Subtype     |
|---------------------------|--------------|-------------|
| manufacturer              | Categorical  | Nominal     |
| name                      | Categorical  | Nominal     |
| category                  | Categorical  | Nominal     |
| gwp_total                 | Numerical    | Continuous  |
| gwp_use_ratio             | Numerical    | Continuous  |
| yearly_tec                | Numerical    | Continuous  |
| lifetime                  | Numerical    | Discrete    |
| use_location              | Categorical  | Nominal     |
| report_date               | Categorical  | Ordinal     |
| gwp_error_ratio           | Numerical    | Continuous  |
| gwp_manufacturing_ratio   | Numerical    | Continuous  |
| weight                    | Numerical    | Continuous  |
| assembly_location         | Categorical  | Nominal     |
| screen_size               | Numerical    | Continuous  |



| Entities       | Variables being used                                                                                                               | 
|----------------|------------------------------------------------------------------------------------------------------------------------------------|
| Municipalities | `lifelime`; `use_location`; `gwp_total`; `gwp_use_ratio`; `yearly_tec`; `category`; `weight`; `assembly_location`; `use_location`; | 
| Manufacturers  | `manufacturer`; `name`; `gwp_manufacturing_ratio`; `gwp_error_ratio`; `weight`; `screen_size`; `lifetime`; `gwp_total`;            | 
| Investors      | `use_location`; `lifetime`; `weight`; `category`; `gwp_total`; `gwp_use_ratio`; `yearly_tec`;                                      | 


