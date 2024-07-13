# VPoser: Variational Human Pose Prior for Body Inverse Kinematics

## Description
The articulated 3D pose of the human body is high-dimensional and complex. 
Many applications make use of a prior distribution over valid human poses, but modeling this distribution is difficult.
Here we present VPoser, a learning based variational human pose prior trained from a large dataset of human poses represented as SMPL bodies.
This body prior can be used as an Inverse Kinematics (IK) solver for many tasks such as fitting a body model to images 
as the main contribution of this repository for [SMPLify-X](https://smpl-x.is.tue.mpg.de/). 
VPoser has the following features: 
 - defines a prior of SMPL pose parameters
 - is end-to-end differentiable
 - provides a way to penalize impossible poses while admitting valid ones
 - effectively models correlations among the joints of the body
 - introduces an efficient, low-dimensional, representation for human pose
 - can be used to generate valid 3D human poses for data-dependent tasks

## Contact
The code in this repository is developed by [Nima Ghorbani](https://nghorbani.github.io/) 
while at [Perceiving Systems](https://ps.is.mpg.de/), Max-Planck Institute for Intelligent Systems, Tübingen, Germany.

If you have any questions you can contact us at [smplx@tuebingen.mpg.de](mailto:smplx@tuebingen.mpg.de).

For commercial licensing, contact [ps-licensing@tue.mpg.de](mailto:ps-licensing@tue.mpg.de)
