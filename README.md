# Travel Planner

This Jupyter Notebook (`travel_planner.ipynb`) is a travel planning assistant that helps users create a day trip itinerary based on their city of interest and personal interests. The notebook uses a state-based workflow to guide the user through the process of inputting their city, interests, and generating an itinerary.

## Usage

1. **Run the Notebook**: Open the `travel_planner.ipynb` file in a Jupyter Notebook environment.
2. **Input City**: The notebook will prompt you to enter the city you want to visit.
3. **Input Interests**: Next, you will be asked to enter your interests (comma-separated) for the city.
4. **Generate Itinerary**: The notebook will generate a day trip itinerary based on your inputs and display it.

## Dependencies

- `os`
- `typing`
- `langgraph`
- `langchain_core`
- `langchain_google_genai`
- `IPython`
- `dotenv`

Make sure to install the required dependencies using the following command:

```bash
pip install langgraph langchain-core langchain-google-genai IPython python-dotenv
```

## Example

To use the travel planner, simply run the notebook and follow the prompts. Here is an example of how the interaction might look:

```
Initial Request: I want to plan a day trip.

Enter the city you want to visit: Pune
Enter the interests you have (comma separated) for the New York: Dagdusheth, Sinhagad

Creating an itinerary for city: Pune with interests: Dagdusheth, Sinhagad

Final Itinerary:
Okay! I can definitely help you plan a day trip from Pune, focusing on Sinhagad Fort, Dagdusheth Halwai Ganpati Temple, and Raigad Fort. However, please note that visiting both Sinhagad and Raigad in a single day is extremely challenging due to the distance between them. It will involve a lot of travel time. Let's make a plan with the understanding that time will be tight. I will provide an itinerary focusing on Sinhagad and Dagdusheth, and then a separate one that focuses on Raigad and Dagdusheth.

**Option 1: Sinhagad & Dagdusheth (Recommended for a more relaxed pace)**

This itinerary focuses on a more manageable day, allowing you to enjoy the attractions without feeling too rushed.

*   **7:00 AM:** Depart from Pune.
*   **8:00 AM:** Arrive at Sinhagad Fort. Explore the fort, enjoy the views, and experience the historical site. (Allow 2-3 hours)
*   **11:00 AM - 12:00 PM:** Enjoy breakfast/lunch at a local restaurant near Sinhagad or pack your own picnic.
*   **12:00 PM:** Depart from Sinhagad.
*   **1:00 PM:** Arrive at Dagdusheth Halwai Ganpati Temple. Offer your prayers and spend some time admiring the beautiful temple. (Allow 1-2 hours)
*   **3:00 PM:** Lunch near Dagdusheth (If not already done).
*   **4:00 PM:** Explore the local shops and markets near Dagdusheth.
*   **5:00 PM:** Start your return journey to Pune.
*   **6:00 PM - 7:00 PM:** Arrive back in Pune.
```
