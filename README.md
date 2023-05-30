# Backend Test

In a world plunged into an apocalyptic nightmare, a catastrophic event has unfolded. 
The emergence of the "Cogni-Virus" (commonly referred to as the C-Virus) has triggered a transformation in human beings, reducing their cognitive abilities and turning them into mindless creatures, known as "Lost Ones."
These unfortunate beings possess an insatiable appetite for chaos and seek to dismantle human society as we once knew it.

However, amidst the devastation, you stand as the final survivor equipped with a unique skill set in coding and technology.
Recognizing the critical role you can play in humanity's survival, you embark on a mission to aid the resistance.
With your expertise, you create a resilient network known as the "Survival Nexus." This system acts as a vital lifeline, enabling the remaining humans to detect new infections, coordinate resources, and bolster their chances of enduring this unprecedented crisis.

## Features

You will develop an API that will allow the resistance to manage their resources and coordinate their efforts.

To accomplish this, the API will need to support the following operations:

- Create survivor
- Update survivor
- Trade items between survivors
- Reports
  - Percentage of infected survivors
  - Percentage of non-infected survivors
  - Average amount of each kind of resource by survivor (e.g. 5 waters per survivor)

## Notes

- This challenge doens't require you to implement 100% of the features but everything you do will be reviewed to check your skills
- Unit test is required
- Ideally write in Typescript with NestJS, but you can use any language you want
- You can use any database you want
- You can use any libraries you want
- Write a minimal README.md with instructions on how to run your project

## Resources

### Survivor

A survivor will have the following attributes:

- name
- age
- gender
- last location (latitude, longitude)
- inventory (items)
  - item id
  - quantity
- infected (boolean)

### Item

- name
- description

Item options are the following:

- Water
- Food
- Medication
- C-Virus Vaccine

## Bonus

- Add authentication to API (JWT, OAuth, etc)
- Log of trades made with their respective survivors
- Dockerize your application

## Submission

After finish your implementation, please send us the link of your repository.

