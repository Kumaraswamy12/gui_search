Here’s a detailed documentation section for your GitHub README file to describe the functionality and usage of your CSV Group and Sub-Name Viewer application. 

---

# CSV Group and Sub-Name Viewer

This application provides a graphical user interface (GUI) to upload and process CSV files containing hierarchical data. Users can explore groups and their sub-names and view associated data conveniently.

## Features

- **File Upload**: Upload a CSV file containing grouped data.
- **Group Selection**: Choose a group from a dropdown list.
- **Sub-Name Search with Suggestions**: Enter or select a sub-name from a dropdown with autocomplete suggestions.
- **Data Display**: View the corresponding data for the selected group and sub-name.

---

## Requirements

Ensure you have the following installed on your system:

- Python 3.7 or higher
- Required libraries:
  - `tkinter` (default with Python)
  - `pandas`

Install additional dependencies using pip:
```bash
pip install pandas
```

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repo-name.git
   cd repo-name
   ```

2. Run the application:
   ```bash
   python app.py
   ```

---

## How to Use

1. **Launch the Application**:
   Run the script to start the GUI.

2. **Upload CSV File**:
   - Click the **"Upload CSV File"** button.
   - Select a valid CSV file containing grouped data.
   - Ensure the file format is as follows:
     ```
     Sheet:Group1
     Sub1,Value1,Value2,Value3
     Sub2,Value4,Value5,Value6

     Sheet:Group2
     Sub1,Value7,Value8,Value9
     Sub2,Value10,Value11,Value12
     ```

3. **Select Group**:
   - Choose a group from the **"Select Group"** dropdown.

4. **Enter or Select Sub-Name**:
   - Start typing a sub-name in the **"Select or Enter Sub-Name"** field.
   - The dropdown will suggest matching sub-names based on your input.
   - Select the desired sub-name.

5. **Display Data**:
   - Click the **"Display Data"** button to view the corresponding data for the selected group and sub-name.
   - The data will appear in the text area below.

---

## Example CSV Structure

Below is an example of a valid CSV structure the application can process:

```
Sheet:Cars
SUV,Value1,Value2,Value3
Sedan,Value4,Value5,Value6

Sheet:Bikes
Sport,Value7,Value8,Value9
Cruiser,Value10,Value11,Value12

Sheet:Trucks
Light,Value13,Value14,Value15
Heavy,Value16,Value17,Value18
```

---

## Screenshots

### Main Interface
![Main Interface](https://github.com/user-attachments/assets/27fd1644-d3f7-45ed-a262-ae7db2e17dee)

### CSV File Upload
![File Upload](https://github.com/user-attachments/assets/964e0c3d-d25d-4368-a2d5-ea688f755f79)
![image](https://github.com/user-attachments/assets/f3224b8f-3cc7-4098-88cb-0a7b09a6aeb0)
![image](https://github.com/user-attachments/assets/ec0bc6f0-30b8-437a-bd8d-df31e7e1d371)



### Data Display
![Data Display](https://github.com/user-attachments/assets/8110196a-71f1-46ae-a4d0-e652d9ed5210)


---

## File Structure

```
repo-name/
│
├── app.py                 # Main application script
├── sample.csv             # Example CSV file
├── README.md              # Documentation
└── requirements.txt       # Required Python dependencies
```

---

## Notes

- The application assumes the first column of the CSV contains group and sub-name identifiers.
- Blank rows in the CSV file are treated as separators.

---

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

--- 

This documentation provides an overview, installation guide, usage instructions, and details for contributing to the project. You can customize it further for your specific repository or preferences. Let me know if you'd like help tweaking any section!
