# Worker Efficiency Prediction Challenge 🚀

This project focuses on analyzing and predicting worker efficiency in a factory setting. The dataset provides various attributes of workers, their roles, and their performance metrics, allowing us to build models to predict efficiency.

## Project Overview 📊

The aim of this project is to explore the dataset, perform data cleaning, feature engineering, and develop machine learning models to predict worker efficiency based on various factors. This project will help understand the key determinants of worker efficiency in a factory environment.

## Dataset Description 📁

The dataset consists of 107.61 MB of CSV files with the following columns:

- **record_ID**: Unique identifier for each record in the dataset.
- **worker_ID**: Unique identifier for each worker.
- **worker_fname**: First name of the worker.
- **worker_lname**: Last name of the worker.
- **worker_age**: Age of the worker.
- **worker_sex**: The sex (“M” or “F”) of the worker who is the record's subject.
- **worker_shift**: The name of the shift on which the event’s subject works. Possible values are “Shift 1”, “Shift 2”, “Shift 3”, or “unassigned”.
- **worker_team**: The name of the team on which the record subject works. Varies based on shift and role, with possible values for shift teams and "unassigned" for specific roles.
- **worker_role**: The organizational role of the employee, such as “Production Director,” “Shift Manager,” “Team Leader,” and “Laborer.”
- **worker_coll_IDs**: A list containing the ID numbers of the other employees who are immediate coworker-peers of the event’s subject.
- **worker_colls_same_sex_prtn**: The portion of the subject’s immediate coworker-peers who are of the same sex.
- **worker_health**: Health status of the worker (value 0-1).
- **worker_commitment**: Level of commitment demonstrated by the worker (value 0-1).
- **worker_perceptiveness**: Ability of the worker to perceive and understand situations effectively (value 0-1).
- **worker_dexterity**: Skill level in terms of manual dexterity.
- **worker_sociality**: The level of interaction and engagement a worker exhibits within their team or with other workers (value 0-1).
- **worker_goodness**: Overall moral character or goodness of the worker (value 0-1).
- **worker_strength**: Physical strength or endurance of the worker (value 0-1).
- **worker_openmindedness**: Degree of openness to new ideas and perspectives (value 0-1).
- **worker_workstyle**: The subject’s “Workstyle group” influences their Efficacy and other behavioral patterns, with possible values “Group A” to “Group E”.
- **chief_id**: Unique identifier for each chief.
- **chief_fname**: The first name of the subject’s chief.
- **chief_lname**: The last name of the subject’s chief.
- **chief_age**: Age of the chief.
- **chief_sub_age_diff**: Age difference between the chief and the worker.
- **chief_sex**: Gender of the chief (male/female/other).
- **chief_role**: Role or position of the chief within the organization.
- **chief_commitment**: Level of commitment demonstrated by the chief.
- **chief_perceptiveness**: Ability of the chief to perceive and understand situations effectively.
- **chief_goodness**: Overall moral character or goodness of the chief.
- **record_date**: Date when the record was created.
- **record_week_in_series**: Week number in the series of records.
- **record_day_in_series**: Day number in the series of records.
- **?**: Unknown.
- **??**: Unknown.
- **efficiency**: Efficiency metric or performance measure, with a minimum value of 0.0 and no maximum.

## Files 📂

The dataset consists of four CSV files, totaling 107.61 MB in size.

## License 📜

This project and its dataset are subject to the terms and conditions specified by the original dataset provider on Kaggle.

## Getting Started 🛠️

1. **Data Exploration**: Understand the structure of the dataset and the meaning of each feature.
2. **Data Cleaning**: Handle missing values, remove duplicates, and preprocess data for analysis.
3. **Feature Engineering**: Create new features that could help improve model performance.
4. **Modeling**: Develop machine learning models to predict worker efficiency.
5. **Evaluation**: Assess model performance using appropriate metrics and validate results.

## Contributing 🤝

Contributions are welcome! Feel free to open issues or submit pull requests for improvements or suggestions.

## Contact 📧

For any questions or inquiries, please contact me at iheblazhary@gmail.com .
