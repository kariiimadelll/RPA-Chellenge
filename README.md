# 🤖 RPA Challenge - UiPath Automation Project

This is an automation project built using **UiPath**, designed to solve the well-known [RPA Challenge](https://rpachallenge.com/).

The challenge involves reading structured data from an Excel file, then inputting that data into a web form where the fields change order after each submission — a perfect test of UI automation and dynamic selectors.

## 🧠 Project Summary

The robot performs the following tasks:

1. Opens the RPA Challenge website.
2. Reads the data from `challenge.xlsx`.
3. Starts the challenge and dynamically identifies form fields.
4. Submits the form for each row.

## 🗂 Project Structure

| File/Folder | Description |
|-------------|-------------|
| `Main.xaml` | Main dispatcher / entry point |
| `challenge.xlsx` | Excel file with the input data |
| `RPA_Challenge/OpeningBrowser.xaml` | Opens browser and site |
| `RPA_Challenge/DataTableExtractedData.xaml` | Reads Excel data, Fills and submits the form |
| `RPA_Challenge/Start Challenge.xaml` | Starts the Challenge|

## ✅ How to Run

1. Open in UiPath Studio
2. Ensure `challenge.xlsx` exists
3. Run `Main.xaml`

## 👤 Author

Created by: *[Karim Adel]*  
First UiPath project 🚀
