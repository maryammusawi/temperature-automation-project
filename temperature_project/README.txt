Temperature Automation Project

Files Included:
- temp_auto.py - Main automation script
- cities.xlsx - Input data (cities in Column A)
- updated_temps.xlsx - Output file (will be created when run)

How to Run:
1. Ensure Python 3 is installed (usually pre-installed on Mac/Windows)
2. Open Terminal/Command Prompt
3. Install requirements (one-time setup):
   pip3 install openpyxl requests
4. Run the automation:
   python3 temp_auto.py

Immediate Testing:
- The script will start and show "Temperature tracker started"
- Press Ctrl+C to stop after seeing the output
- Check updated_temps.xlsx for results

Features Demonstrated:
- Excel file automation (read/write)
- API integration (OpenWeatherMap)
- Real-time temperature data fetching
- Error handling and logging
- Low-code development approach
- Automated scheduling capability

Assignment Requirements Met:
- Objective: Automate temperature data collection from API to Excel
- Input: Excel file with city names (Column A)
- Output: Updated Excel with temperatures (Column B) and conditions (Column C)
- Documentation: This README + code comments

Automation Schedule:
- Script is designed to run continuously
- Auto-updates daily at 8:00 AM
- For testing: Run once and stop with Ctrl+C

Technical Notes:
- Requires internet connection for API access
- Uses free OpenWeatherMap API key
- Compatible with macOS, Windows, Linux
- No complex setup or background processes needed

Support:
If any issues occur:
1. Ensure all files are in the same folder
2. Check internet connection
3. Verify Python 3.6+ is installed

