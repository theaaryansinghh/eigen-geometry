# Eigen Geometry
Eigenvalues are not numbers, they are behavior.

## What this is
A minimal interactive visualization to understand eigenvalues and eigenvectors as geometric transformations, not just algebraic outputs.

## History
The idea originates from studying quadratic forms and linear transformations.

- Leonhard Euler worked on early matrix-like structures
- Augustin-Louis Cauchy formalized eigenvalues in the context of matrices
- Later, David Hilbert and others pushed it into functional analysis

Eigenvalues were never meant to be "just solved". They describe intrinsic behavior of transformations.

## The people behind it

**Euler, 1743**
Euler was working on the rotation of rigid bodies, not matrices. He needed to find axes that stayed fixed under rotation. He did not call them eigenvectors. He did not have that language. He just noticed that some directions did not move, and he used that fact to solve the problem. The abstraction came later.

**Cauchy, 1829**
Cauchy was the one who made it algebraic. He proved that symmetric matrices always have real eigenvalues, which at the time was not obvious at all. He was also one of the most prolific mathematicians in history, second only to Euler in number of published pages. He did much of this work while in self-imposed exile after the fall of Napoleon, writing papers from Turin and Prague, sending them back to Paris to be read aloud at the Academy while he was not there to defend them.

**Cayley and Sylvester, 1850s**
Arthur Cayley invented matrix notation as we know it. His friend James Sylvester coined the word "matrix" itself, from the Latin for womb, because he thought of it as something that generated determinants. The two of them spent years exchanging letters working out the algebra. Neither had a university position for much of this period. Sylvester spent years working as an actuary and a lawyer before getting a professorship. Cayley practiced law for fourteen years while doing mathematics on the side.

**Hilbert, 1904**
David Hilbert extended eigenvalues into infinite dimensions while studying integral equations. He called them eigenwerte, German for "own values", which is where the prefix eigen comes from. The word was a deliberate choice. He meant values that belong to the transformation itself, not to any particular coordinate system. When the theory was translated into English, nobody translated the prefix. It stayed eigen.

**Heisenberg, 1925**
Werner Heisenberg independently rediscovered matrix mechanics while trying to describe atomic spectra. He was twenty-three. He did not recognize that what he had written down were matrices because he had never studied them. Max Born, his advisor, looked at the arrays of numbers and said: those are matrices. The eigenvalues of Heisenberg's energy matrix turned out to be the exact frequencies of light emitted by hydrogen. This was not a coincidence. It was the structure of quantum mechanics.

## The problem with how it's taught
Most courses:

- start with determinants
- reduce eigenvalues to a computation problem
- ignore geometric meaning

So people can solve them but don't understand them.

## What this project does

- shows transformations directly
- lets you observe invariant directions (eigenvectors)
- makes scaling (eigenvalues) visible

You see first, compute later.

## Run locally
Clone the repo:

```bash
git clone https://github.com/theaaryansinghh/eigen-geometry.git
cd eigen-geometry
```

Open `index.html` in any browser. No dependencies, no build step.