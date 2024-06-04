# Solar System Simulation

<img width="1277" alt="Zrzut ekranu 2024-05-18 o 17 28 20" src="https://github.com/JoanKr/ruch-planet/assets/125133969/ab29fc27-83ed-429c-bce2-0eac5d175bf9">


This project is a WebGL-based simulation of the Solar System. It visualizes the planets orbiting the Sun with realistic proportions and speeds.

## Features

- Realistic proportions of planets and their orbits
- Correct orbital and rotational speeds of the planets
- Basic keyboard controls to navigate the scene
  - `W` to zoom in
  - `S` to zoom out
  - `A` to move left
  - `D` to move right

## Getting Started

### Prerequisites

To run this project, you need a web browser that supports WebGL and a Live Server to serve the files.

### Running the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/JoanKr/ruch-planet.git
    ```
2. Open the project directory:
    ```bash
    cd ruch-planet
    ```
3. Start the Live Server (you can use extensions like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code).
4. Open the `index.html` file through the Live Server.

### File Structure

- `index.html`: Main HTML file containing the WebGL setup and the simulation logic.
- `textures/`: Directory containing texture images for the planets.

### Simulation Details

The simulation includes the following planets with their corresponding orbital speeds (relative to each other):

- **Sun**: Stationary in the center
- **Mercury**: Orbit speed - 1.185
- **Venus**: Orbit speed - 0.875
- **Earth**: Orbit speed - 0.745
- **Mars**: Orbit speed - 0.6025
- **Jupiter**: Orbit speed - 0.3275
- **Saturn**: Orbit speed - 0.2425
- **Uranus**: Orbit speed - 0.17
- **Neptune**: Orbit speed - 0.135

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

- Thanks to the creators of WebGL for making 3D graphics in the browser possible.
- Inspired by the beauty of our Solar System.
