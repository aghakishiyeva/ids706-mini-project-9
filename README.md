# Performing a Data Manipulation task on Cloud-Hosted Notebook [Google Colaboratory]

Steps to Connect Dataset from GitHub with Google Colab and Save to GitHub:

**1. Find Dataset on GitHub:**<br>
1.1. Navigate to the file in your GitHub repository.<br>
1.2. Click on the file (e.g., a CSV file) to view its contents.<br>
1.3. Click on the “Raw” button. This will take you to a plain text version of the file.<br>
1.4. Copy the URL from your browser’s address bar. This is the direct link to the raw data file.<br><br>

**2. Open Google Colab:**<br>
2.1. Go to Google Colab.<br>
2.2. Click on “New Notebook”.<br><br>

**3. Start Coding:**<br>
3.1. You’ll see a code cell opened.<br>
3.2. Start writing your code:<br><br>

```bash
Copy code
import pandas as pd

# Read dataset
data_path = "https://raw.githubusercontent.com/aghakishiyeva/ids706-mini-project-9/main/data/winequality-red.csv"
data = pd.read_csv(data_path)
data.head()

```
**4. Save Notebook to GitHub:**<br>
4.1. After completing your code, click on File -> Save a copy in GitHub.<br>
4.2. In the page opened, click “Authorize googlecolab”.<br>
4.3. Enter the password of your Google Colab account.<br>
4.4. In the tab where you work on the Google Colab Notebook, a window will appear, where you’ll choose your repository.<br>

![Screenshot 2023-10-30 at 17 06 35](https://github.com/aghakishiyeva/ids706-mini-project-9/assets/78721466/ef15c378-558c-4222-ba29-c3a3512d8690)

4.5. Choose the repository and click OK.<br><br>

**5. Sync Changes:**<br>
5.1. Now you have connected your notebook with your GitHub repository and you can save your changes to the repo whenever you want.<br><br>

This README provides a structured and clear set of instructions for anyone looking to connect a GitHub dataset to Google Colab and sync their notebook with a GitHub repository.
