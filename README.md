# Machine Learning and I

## Introduction

### Interests

First and foremost, my interest lies in the fields of [Cross-Language Interoperability](https://en.wikipedia.org/wiki/Language_interoperability) and [Performance Engineering](https://en.wikipedia.org/wiki/Performance_engineering), rather than Machine Learning. And this determined the concepts, principles, and technologies that I learned and used in my projects.

Having said that, I also deeply love Mathematics and - as a Software Engineer - I especially care about the discrete rather than continuous parts of it. For instance, recently (as of March 16, 2025), I was having fun with the extension of [Morton order](https://en.wikipedia.org/wiki/Z-order_curve) to arbitrary 2D shapes of matrices (which can be used, for example, for efficient \[= with high cache locality\] diamond-shaped-pattern access to 2D images or game maps). You can find the Google Colab notebook with the code and explanations [here](https://colab.research.google.com/drive/1yO0iNEWpQeGmWP4_m8_CqCqlcRGAZ2oj?usp=sharing).

*Note: I never intended to share it with anyone in the foreseeable future, but I decided to do it here because it well demonstrates my mathematical interests (but not my programming skills because the code there was meant to be a throw-away code).*

### Professional Backgroung

Throughout my career, I have been primarily working as a Backend, Full-Stack, or Cross-Platform developer, where were many opportunities to apply my interests, skills, and knowledge. You can learn more about my commercial programming story at <https://github.com/JohnScience/my_com_projs>.

## Programming Skills

*Note: many of the skills that are deemed to be connected to ML too remotely are omitted.*

### Languages

- **Programming Languages**: Python, C, C++, Rust, ...
- **Query Languages**: SQL (PostgreSQL, MySQL, SQLite, ~~TSQL~~), Cypher, ...
- **Documentation**: Markdown, Jupyter Notebooks, mdBook, TeX (+expl3), BibTex.

### Source Code Management

- **Version Control**: `git`, `gh`, Git hooks (pre-commit).
- **Formatting**:
    * **Python:**: `black`, `autopep8`.
    * **Rust**: `rustfmt`.
    * **C/C++**: `clang-format`.
    * ...
- **Linting**:
    * **Python:**: `flake8`, `pylint`, `ruff`.
    * **Rust**: `clippy`.
    * **C/C++**: `clang-tidy`.
    * ...
- **Automated Code Review**: CodeRabbit. 
- **CI/CD**: GitHub Actions, [`act`](https://github.com/nektos/act).

### Package and Environment Management

- **Language-Package and Environment Management**:
    * **Python:**: `poetry`, `conda`, `virtualenv`, `venv`, `pip install -r requirements.txt`.
    * **Rust**: `cargo`.
    * **C/C++**: `cmake`, `vcpkg`.
    * ...
- **System Package Management**:
    * **Linux**: `apt`, `pkg-config`.
    * **Windows**: `winget`, `choco`, `scoop`.
    * **MacOS**: `brew`.

### Cloud

- **Cloud Services**: AWS (S3, EC2, SageMaker, Bedrock, Transcribe, Polly, ...), GCP (GCS, GCE, ...), ~~Azure~~.
- **Infrastructure as Code**: AWS CDK, ~~Terraform~~ (TBD).
- **Containerization**: Docker, Docker Compose, Podman.
- **Orchestration**: Kubernetes.
- **Local Development**: LocalStack, minikube.

### Tools

- Linux Shell (WSL):
    * `grep` (`ripgrep`)
    * `sed` (`sd`)
    * `ls` (`exa`)
    * `jq`
    * ...
- `ngrok`
- `cargo-make` (for cross-platform shell)
- Triton Inference Server

### Python Libraries

#### For ML

- **General Purpose Computing**: `numpy`.
- **Data Frames**: `pandas`, `polars`.
- **Image processing**: `scikit-image`, Pillow, ~~OpenCV~~.
- **Machine Learning**:
    * **Traditional**: ~~`scikit-learn`~~.
    * **Deep Learning**: `pytorch`, ~~`tensorflow`~~, ~~`keras`~~.
- **Natural Language Processing**: `nltk`.
- **Plotting**: `matplotlib`.

#### For interoperability

- **C/C++ Interoperability**: `ctypes`, `cffi`, SWIG.
- **Rust Interoperability**: `pyo3`.
- **WASM**: `wasmer-python`.

### Rust (for Python Extensions)

- **Python Bindings**: `pyo3`.
- **Python Packaging**: `maturin`.

## Mathematical Skills and Knowledge (for ML)

- **Category and Set Theory**: provides a foundation for the out-of-the-box thinking about the structure of the data and the problems.
- **Linear Algebra**: matrix operations, eigenvectors, eigenvalues, ...
- **Calculus**: derivatives, integrals, ...
- **Multivariable Calculus**: gradients, Jacobians, ...
- **Discrete Calculus**: derivatives->differences, integrals->Riemann sums, ...
- **Statistics**: probability, distributions, ...
- **Optimization**: gradient descent, ...
- **Combinatorics**: permutations, combinations, ...
- **Information Theory**: entropy, mutual information, ...
- **Graph Theory**: Hamiltonian paths, ...
- **Supervised Learning**:
    * Classification: KNN, Decision Trees.
    * Regression: Linear Regression, K-Nearest Neighbors Regression.
- **Unsupervised Learning**:
    * Clustering: k-means.
    * Dimensionality reduction: ~~PCA~~, Singular Value Decomposition.

*Note: I also watched 3Blue1Brown's series specifically on [Neural Networks](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&ab_channel=3Blue1Brown) and [Deep Learning](https://www.youtube.com/watch?v=aircAruvnKk&list=PLcCe-ymWq77ow42k4-ZrLzlM3F7Ha7smT)*.

## Experience

I have little experience with ML itself, but I have been working on projects where ML was used. You can learn more about my experiences at <https://github.com/JohnScience/my_ml_projs>.

*TODO: Add more details for convenience and add stories from hackathons/datathons*.

## On the origin of this repository

This repository was created as a response for NextAI's questionnaire on ML ethos at the company. Next AI is a development program for entrepreneurs featuring structured education to support innovative ideas.
