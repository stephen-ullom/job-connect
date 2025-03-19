# Job-Connect

A streamlined LinkedIn automation tool designed to simplify the job search and application process for software
engineers. This intuitive application, built with Python and PyQt5, seamlessly integrates with LinkedIn, allowing users
to fetch job listings, identify recruiters, and automate application submissions directly from their desktop. Key
features include job scraping, recruiter contact retrieval, customizable email templates, and automated job
applications, all managed through a user-friendly interface. Ideal for job seekers looking to optimize their search with
minimal effort.

## Installation

Follow these steps to set up the project:

1. **Install Dependencies**

```sh
pip install -r requirements.txt
```

2. **Copy the Environment File**

```sh
cp .env.copy .env
```

3. **Copy the Default Configuration File**

```sh
cp default-config.json config.json
```

4. **Run app**

```sh
python main.py
```

More steps to come later, for now these commands are just for me to remember

`conda activate myenv`

`pyuic5 jobconnect.ui -o ui.py`

### Nice to Have

- [ ] Log jobs applied to
- [ ] Track salary
- [ ] Track remote
- [ ] Track seniority
