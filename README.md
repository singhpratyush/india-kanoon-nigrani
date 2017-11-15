# Indian Kanoon Nigrani

### Usage

##### Install dependencies

- Install pipenv
  ```bash
  sudo -H pip install pipenv
  ```
- Install dependencies
  ```bash
  pipenv install
  ```

##### Running project

```bash
sudo service elasticsearch start  # Start elasticsearch
pipenv shell
python india-kanoon-nigrani/start.py <number of threads>
```

**Note:** The rate limit is quite strict, so use only one thread. But if you are really in need and want to get blocked, 16 is fun :wink:.
