# Data quality report
- Imputing missing category values addresses completeness.
- Rounding imputed profit to 2 decimals addresses validity. Here ensures the resulting monetary values follow the expected decimal format.
- Removing exact duplicate rows addresses uniqueness. Because this ensures the same record is not represented more than once.
- Imputing profit_inr using category mean margin addresses completeness. Here replacing missing profit values with calculated values.