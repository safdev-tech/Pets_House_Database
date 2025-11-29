# Pets House Database

This is a collaborative initiative, which consists of a database of pets managed by an adoption agency.
The database contains three main tables, such as: species table, pet house table, adoption table.
The goal of this database is to streamline the tracking and management of pets within the adoption process,
enabling insightful analyses to improve adoption rates and outcomes. The design ensures clear relationships between pets, their species, and adoption
records. The foreign keys establish links for querying data across tables, enabling comprehensive analysis of adoption trends and pet profiles.

Species table:
Define species types, breed, and primary keys for unique identification.

Pet House table:
Includes pet attributes, namely: age, health and shelter metrics.

Adoption table:
Tracks adoption details, including fees, dates and pet identifiers.


Question
What are the factors Influencing Pet Adoption Likelihood?

Extraction and Queries

1. What Pet Type and Breed have the highest likelihood of being adopted?

Findings:
a. Dogs were the most adopted pet type.
b. Among dogs, Labradors were the most popular breed.
c. For all pet types, Parakeets were the most adopted breed.

2. How do vaccination and health status impact high adoption likelihood?

Findings:
- Pets that were vaccinated and in good health had the highest likelihood of being
adopted.
Unvaccinated and unhealthy pets were less likely to be adopted.
- Surprisingly, people preferred healthy and unvaccinated pets to unhealthy and
vaccinated pets.

3. Were the pets who spent more time in the shelter less likely to be adopted?

Findings: Pets with a low likelihood to get adopted on average, spent more time in the
shelter, However, the difference was 5 days so it is not really significant.

4. What impact does having a previous owner have on your likelihood of being adopted?

Findings:
Pets without a previous owner(195)
Pets with a previous owner(106)
Percentage of high likelihood adoption:-
With a previous owner: 72.64
Without previous owner: 82.05
Those without a previous owner are more likely to be adopted.

Recommendations:
1. Prioritize Vaccination and Healthcare:
Ensure all pets in the shelter receive proper vaccinations and healthcare to improve their
adoption prospects.

2. Highlight Popular Breeds and Pet Types:
Focus promotional efforts on breeds and pet types with higher adoption rates, such as
Labradors among dogs and Parakeets among birds, to attract more potential adopters.

3. Reduce Shelter Stay Times:
Implement strategies to shorten shelter stays, such as early adopter engagement or
targeted marketing campaigns. While the impact of shelter time on adoption likelihood is
minimal, shorter stays could still enhance overall shelter operations.

4. Promote Pets Without Previous Owners:
Showcase pets without prior ownership more prominently in adoption listings. Potential
adopters may prefer these pets as they might represent a fresh start or avoid concerns
about why a pet was returned.

References:
Rabie El kharoua. (2024). Predict Pet Adoption Status Dataset. Kaggle.
https://doi.org/10.34740/KAGGLE/DS/5242440
