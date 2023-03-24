# Star Pattern Localization

This is a neural network for deriving the position and orientation of a camera in space, given an image of the stars taken at a position within 1000 light-years of the solar system. Work in progress.

### Abstract:

&emsp;Because of the time delay in receiving signals from Earth, interstellar missions will
require autonomous navigation systems capable of calculating their position, attitude, and
velocity based on limited information from natural galactic phenomena. As traditional star
tracking methods will fail in interstellar space due to parallax, new methods will be required
to solve this “lost-in-space” problem. This project explores the use of convolutional neural
networks for position and attitude determination from photographic data of stars. Simulated
images taken from locations within the Milky Way will be generated using a subset of the
Gaia DR3 database of star positions and rendered using Gaia Sky. These images will be used
to train a neural network to predict the position and attitude of the camera within the Milky
Way. As neural networks are prone to error and uncertainty, this system could be used as a
heuristic in another search algorithm to localize an interstellar spacecraft, providing a
tractable solution to the lost-in-space problem.
