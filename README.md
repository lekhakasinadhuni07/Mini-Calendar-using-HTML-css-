# Mini Calendar using HTML, CSS, and JavaScript
## Description
This project is a mini calendar application developed using HTML, CSS, and JavaScript. It shows the current month and year and allows users to browse through months. The calendar updates dynamically as the user navigates through different months, providing an easy-to-use interface that works on various screen sizes.

![image Alt](https://github.com/lekhakasinadhuni07/Mini-Calendar-using-HTML-css-/blob/041a8e12fa837141abf803026c703d26d53e6bb6/Mini-calendar.png)

## Features
- Current Month and Year Display: Shows the current month, year, and all the days of the month.
- Dynamic Update: The calendar dynamically updates to show the correct days for each month.
- Responsive Design: The layout is responsive, adapting to mobile and desktop screens.
- Current Day Highlight: The current day is highlighted for easy recognition.
## Usage
- The calendar dynamically updates to show the correct number of days for each month.
- The current day will be highlighted for quick reference.
## Code Structure
- HTML: Defines the structure of the calendar, including the month, year, and days.
- CSS: Styles the calendar, ensuring responsiveness and highlighting the current day.
- JavaScript: Handles the logic for updating the calendar as the user navigates through different months.
```html
*{
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    box-sizing: border-box;
}
.hero{
    width: 100%;
    min-height: 100vh;
    background: linear-gradient(45deg, #1d0000, #20205b);
    display: flex;
    align-items: center;
    justify-content: center;
}
.calendar{
    width: 300px;
    height: 250px;
    background: #fff;
    display: flex;
    align-items: center;
    border-radius:10px;
}
.left, .right{
    
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    font-size: 24px;
}
.right{
    width: 42%;
    background: rgb(136, 23, 130);
    color: #fff;
    border-bottom-right-radius: 10px;
}
.left{
    width: 58%;
}
#date{
    font-size: 100px;
    line-height: 90px;
    
}
```
