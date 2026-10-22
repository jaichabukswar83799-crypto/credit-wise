# Credit Wise

Credit Wise is a Jupyter notebook project for exploring loan approval data and
training classification models.

## Project files

- [`credit_wise.ipynb`](credit_wise.ipynb): notebook with the analysis and model
  training code.
- [`requirements.txt`](requirements.txt): Python packages used by the notebook.

## Run the notebook

1. Install Python and Jupyter.
2. Install the project dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

3. Place the authorized project dataset at `loan_approval_data.csv` in the
   project folder. The notebook reads this relative path in its first data
   loading cell.
4. Start Jupyter and open `credit_wise.ipynb`.

The dataset was not present in the project folder when this repository was
prepared, so the notebook cannot run end-to-end until you add that CSV. Do not
publish applicant or other personal data unless you are authorized to share it.
