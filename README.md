# Pull Request Prediction

## Setup

To set up the project and install the required dependencies, follow these instructions:

##### Make sure that git-lfs is installed before cloning the repository.

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/pull-request-prediction.git
   cd pull-request-prediction
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment:**

- On Windows:
  ```bash
  venv\Scripts\activate
  ```
- On macOS/Linux
  ```bash
  source venv/bin/activate
  ```

4. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

5. **Unzip 'gerrit_eclipse.csv.gz':**

   ```bash
   gunzip gerrit_eclipse.csv.gz
   ```
