# Blood Type Inheritance Simulation

## Project Overview

This C program simulates the genetic inheritance of blood types across multiple generations of a family tree. It demonstrates how blood type alleles (A, B, and O) are passed from parents to children according to genetic inheritance patterns, creating a realistic family lineage with corresponding blood types.

## How It Works

The program creates a family tree with three generations and simulates the inheritance of blood type alleles:

1. Each person has two alleles that determine their blood type (A, B, or O)
2. Children randomly inherit one allele from each parent
3. The program recursively builds a family tree, starting with the youngest generation
4. Blood types are determined by the combination of alleles:
   - Two identical alleles (AA, BB, OO) result in that blood type
   - AB results in AB blood type
   - AO results in A blood type
   - BO results in B blood type

## Technical Implementation

The program uses:
- Recursive functions to create and navigate the family tree
- Dynamic memory allocation for creating person structures
- Random number generation to simulate genetic inheritance
- Pointer manipulation to establish parent-child relationships

## Usage

Compile the program with:
```
gcc -o inheritance inheritance.c
```

Run the program:
```
./inheritance
```

The output will display a family tree showing the blood type of each family member across three generations.

## Future Development Potential

This project could be extended for digital health applications in several ways:

1. Expanding to include more complex genetic traits and inheritance patterns
2. Adding visualization components for clearer representation of inheritance patterns
3. Incorporating real genetic data to model specific inherited conditions
4. Developing a predictive tool for genetic counseling applications

## Skills Demonstrated

- C programming and memory management
- Data structures (structs and pointers)
- Recursive algorithms
- Genetic inheritance modeling
- Computational biology concepts

## Relevance to Potsdam University Digital Health Master's

This project demonstrates:

1. The application of IT concepts to healthcare problems
2. Understanding of basic medical/genetic concepts
3. Interdisciplinary thinking between computer science and healthcare
4. Potential for innovation in healthcare education and genetic counseling
