# On a Wing and a Prayer EGR 115
This is a group project with team members Alessandra Ozuna, Jacob Henderson, Delmer (Jay) Camp, Aeryn Paet, and Kira Schweikert. 
This code calculates and displays the deflection along a wing of selected materials at variable velocities and altitudes.

## Project Results
![Plane Wing with and without Deflection](images/Plane_Wing.png)
![Deflection Graph](images/Graph_of_Deflection_Path.png)

## Overview
The Wing Deflection Calculator is designed to estimate the structural deflection of aircraft wings under aerodynamic loading. The program models a simplified cantilever beam representation of an aircraft wing and calculates the resulting deformation based on flight conditions, aircraft geometry, and material properties. By allowing users to select different aircraft configurations and wing materials, the tool demonstrates how aerodynamic forces and structural stiffness influence wing performance during flight.

Aircraft data such as wingspan and reference wing area are stored within dictionaries, allowing the program to simulate multiple aircraft types ranging from sailplanes to large commercial transport aircraft like Boeing 787 and Lockheed C-5 Galaxy. Material properties are incorporated through their Young's Modulus values, enabling comparisons between normal aerospace materials such as carbon fiber, aluminium alloys, titanium, and traditional wooden structures.
