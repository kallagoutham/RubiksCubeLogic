# Rubik's Cube Solution Guide

## Step 1: Choose the First Color

- Start by choosing the first color to solve.
- Create a "plus" shape on one face by placing pieces with the same color adjacent to the center.

## Step 2: Solve the First Color

- Use the following algorithms to position pieces correctly:
    - Up: ``` U R U' R' (3 times) ```
    - Down: ``` U R U' R' (2 times) ```
    - Up-right: ``` R U R' U' (1 time) ```
- Ensure that all the "T" shapes are aligned with their respective centers.

## Step 3: Solve the Second Layer

- Adjust the center and solve the colors using the formula:
    - ``` R U R U R U' R' U' R' ```

## Step 4: Create a Cross on the Top Face

- If a cross is not visible on the top face, use the following formula:
    - ``` F R U R' U' F' ```

## Step 5: Solve the Top Face Colors

- Use the following algorithms to solve the top face colors without changing the orientation of the cube:
    - Facing Right: ``` R D R' D' ```
    - Facing Front:  ``` D R D' R' ```

## Step 6: Align Middlemost Pieces

- If you find a color solved in a manner where only the top layer middlemost piece is solved or unsolved, place it facing left by matching and use this formula:
    - ``` R U R' U' R' F R R U' R' U' R U R' F' ```

## Step 7: Complete the Cube

- Use the following formula one or two times (according to need) with the solved side facing front:
    - ``` R U' R U R U R U' R' U' R R ```

Congratulations, you've solved the Rubik's Cube!
