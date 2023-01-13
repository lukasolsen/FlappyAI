
#  FlappyAI

  

![FlappyAI](https://imageio.forbes.com/specials-images/imageserve/621edb0064db88ccfcec6462/0x0.jpg?format=jpg&crop=4823,3238,x735,y238,safe&width=800)

  

FlappyAI is a modified and edited version of the original Flappy Bird AI created by Tech With Tim. We have implemented additional features and functionality to enhance the overall gameplay experience. The AI utilizes a NeuroEvolution of Augmenting Topologies (NEAT) algorithm to train the agents to play the game.

  

##  Team

- Developer 1

- Developer 2

- Developer 3

  

##  About

FlappyAI is an artificial intelligence (AI) model that has been trained to play the popular mobile game, Flappy Bird. The AI utilizes a NeuroEvolution of Augmenting Topologies (NEAT) algorithm to train the agents to play the game. The NEAT algorithm is a type of evolutionary algorithm that is used to evolve artificial neural networks. In this case, the NEAT algorithm is used to evolve the neural networks of the agents that play the game.

  

The AI has been able to achieve a high level of performance and is able to successfully play the game at a very high level.

  

##  Installation

  

To use FlappyAI, you will need to have the following modules installed:

- pygame

- neat-python

- matplotlib

  

You can install these modules by running the following command:

    pip install pygame neat-python matplotlib
   
## API 
We have also implemented a simple API that allows you to interact with the AI and access its functionality. Here is an example of how you can use the API in Python: 
```
import Api.flappy_bird as api

# Initialize the API

# generations_amount: number of generations to train the AI for

# stats_path: file path to save the statistics of the AI training

# images_folder: folder path to save the images of the AI playing the game

api_instance = api.Api(generations_amount=10, stats_path="stats", images_folder="imgs")

  

# Run the API

# max_score: the maximum score the AI should try to reach

api_instance.run(max_score=10)
```

## Warning

Please note that the AI has been trained using the specified modules, if you use any other version of these modules it may not work as intended.

## Acknowledgements

We would like to thank Tech With Tim for providing the original source code for the Flappy Bird AI. You can find Tech With Tim's socials here:

-   Youtube: [Tech With Tim](https://www.youtube.com/c/techwithtim)
-   Twitter: [@techwithtim](https://twitter.com/techwithtim)
-   Instagram: [@techwithtim](https://www.instagram.com/techwithtim/)
-   Website: [techwithtim.net](https://techwithtim.net/)

We would also like to thank the creators of the NEAT algorithm, Kenneth O. Stanley and Risto Miikkulainen for their work on the algorithm. You can find a guide to the NEAT algorithm here: [A guide to the NEAT Algorithm](https://neat-python.readthedocs.io/en/latest/)

## Contribution

If you would like to contribute to the project, please feel free to fork the repository and make a pull request with your changes.

## License
The MIT License (MIT) Copyright (c) [2023] [Lukas Olsen] Permission is hereby granted, free  of charge, to  any person obtaining a copy  of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the
