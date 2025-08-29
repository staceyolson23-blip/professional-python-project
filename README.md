# professional-python-project

## Author
Stacey Olson

## Project Description
This project is part of **Data Analytics Fundamentals (CC1.4: Start a Professional Python Project)**.  
It demonstrates professional Python practices including:

- Using a virtual environment (`.venv`)
- Installing dependencies from `requirements.txt`
- Using logging with `loguru`
- Declaring and using variables (bool, int, str, list, stats)
- Creating a reusable **byline module** with `get_byline()`
- Adding an optional **text-to-speech feature** with `pyttsx3`
- Running Python modules with a `main()` function and  
  `if __name__ == "__main__": main()`

## Files
- `utils_stacey.py` → My custom reusable module
- `requirements.txt` → Dependencies list
- `.gitignore` → Git ignore rules
- `project.log` → Logging output
- `README.md` → Project description and notes

## Example Output
When running `python3 utils_stacey.py`, the project prints a byline:

Analytics for Teachers - Project Header

Author: Stacey Olson
Motto: Because they are busy enough.
Location: Santa Rosa, CA
Years Active: 5
Number of Employees: 25
Accepting New Clients?: True
Remote Workshops?: True
Services: ['Student Data Analysis', 'Curriculum Insights', 'Classroom Dashboards', 'Survey Analytics', 'Professional Development Reports']
Office Locations: ['Santa Rosa', 'Windsor', 'Petaluma']
Client Satisfaction Scores: [4.8, 4.6, 4.9, 5.0, 4.7]
Minimum Satisfaction Score: 4.6
Maximum Satisfaction Score: 5.0
Mean Satisfaction Score: 4.80
Standard Deviation: 0.16