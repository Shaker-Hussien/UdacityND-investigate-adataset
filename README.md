## Project 
### Investigate a Dataset (No-Show Appointments)

## Project Context
- This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.
    - ‘ScheduledDay’ tells us on what day the patient set up their appointment.
    - ‘Neighborhood’ indicates the location of the hospital.
    - ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
    - Be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

- The Questions We Want to Answer is:
    - What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?

## Data Source
- No-show Appointments \
original source [kaggle](https://www.kaggle.com/joniarroba/noshowappointments)


# How To Run

1. Create Virtual Environment using virtualenv and activate it

    ``
    virtualenv venv 
    ``
    then
    ``
    .\venv\Scripts\activate
    ``

2. Install Required Packages Numpy & Pandas for analysis and matplotlib & seaborn for visualization

    ``pip  install numpy pandas matplotlib seaborn jupyter``

3. Run jupyter then run the notebook `` no-show-appointments.ipynb ``

    ``jupyter notebook``

4. HTML file containing analysis are exported from the notebook under name `` no-show-appointments.html ``

