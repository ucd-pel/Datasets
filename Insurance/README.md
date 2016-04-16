Insurance Dataset Description
---------------

This dataset represents the information collected from people about their age, occupation, workplace, favorite recreational activity and places where this is practiced. Such information corresponds to a set of attributes that can be of interest to an insurance company carrying out a risk assessment on potential clients. For example, to help identify groups with a higher risk of having an accident with the purpose of increasing the premium of their insurance policy. This data was generated based on real information. For example, the salary class depends on the occupation and the number of years of work experience that a person has. Similarly, the gender distribution depends on a person's occupation (e.g., the nursing profession remains overwhelmingly female). Such information was obtained from the Payscale USA website (http://www.payscale.com/research/US/Country=United_States/Salary).

### Characteristics

The generated datasets contain the following attributes:

* Gender: 2 values assigned based on the occupation. {female,male}
* Age: 54 numeric values that range between 21-75. 
* Semantic Age: 7 semantic concepts for age. {twenties,thirties,forties,fifties,sixties,seventies}
* Occupation: 60 values. {advocate, agriculturist, architect, assistant_professor, associate_professor, ballet_dancer, baseball_coach, basketball_coach, beekeeper, breeder, cardiologist, chemist, chiropractor, choreographer, civil_engineer, clinical_psychologist, composer, copilot, criminologist, decorator, demonstrator, dentist, dishwasher, divorce_lawyer, electrician, esthetician, general_practitioner, graphic_designer, journalist, lecturer, magician, massager, math_teacher, mime, miner, movie_actor, music_teacher, nurse, nutritionist, opera_star, optometrist, pediatrician, pharmacist, physicist, pianist, pilot, post_doc, public_defender, school_principal, sculptor, software_engineer, street_cleaner, surgeon, tamer, tap_dancer, taster, veterinarian, violinist, visiting_professor, window_cleaner}
* Workplace: 29 values associated with the occupation. {beauty_salon, concert_hall, court, courtroom, gym, hospital, house, massage_parlor, office, pharmacy, restaurant, school, science_lab, surgery, tavern, theatre, university, airport, architecture, circus, countryside, farm, street, studio, heights, location, mine, sky, zoo}
* Activity: 40 values. {bingo, darts, marbles, squash, water-skiing, fishing, swimming, volleyball, billiards, snorkeling, jump_rope, tennis, chess, table_tennis, basketball, bowling, dominoes, scuba_diving, dancing, golf, running, ice_skating, rock_climbing, boxing, baseball, bicycling, surfing, hurling, judo, roller_skating, hunting, soccer, auto_racing, horse_racing, boat_racing, wrestling, rugby, gymnastics, ice_hockey, american_football}
* Place of Activity: 32 values associated with the activity. {volleyball_court, gym, ballpark, park, basketball_court, hippodrome, bar, boxing_ring, coffee_shop, wrestling_ring, tennis_court, squash_court, casino, ballroom, cafeteria, creek, pub, golf_course, cinder_track, football_field, amusement_park, swimming_pool, river, lake, wall_rock, skating_rink, street, forest, racing_circuit, jungle, sea, cave}
* Risk of Accident: 3 classes (low, medium, high) assigned based on the semantic age, occupation, workplace, activity and place of activity.
* Salary: 3 classes (50K, >50K<=100K, >100K) assigned based on the semantic age and occupation.
