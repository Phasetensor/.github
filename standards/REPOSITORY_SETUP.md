# Repository setup

Create a public repository only after the project is accepted for development. Initialize the default branch, enable issue tracking and private vulnerability reporting where available, and configure the PhaseTensor Python CI starter workflow from the Actions tab. Adapt the Python matrix and dependencies to the project's pyproject.toml; verify all checks before making them required. Require review and passing checks on the default branch where supported.

For PyPI, verify name availability, configure a project-specific trusted publisher and a protected release environment, and grant id-token: write only to the publishing job. Build and inspect distributions before publishing. Do not enable automatic publication from ordinary pushes. Release workflows must be tested and configured per repository.

ShotWeave is the first development priority. Its repository should contain a project-specific README, approved license, package metadata, source, tests, examples, benchmark protocol and documentation. No installation or release claims until verified.
