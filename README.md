# Setup
1. `python3.11 -m venv venv`
2. Activate environment (platform dependant)
3. `pip install --upgrade -r requirements.txt`

# Homework 3
1. Set credentials in `config/config.json` obtained from https://my.telegram.org/apps
2. `cd HW3`
3. `cd telegram-data-collection`
4. `python 0_download_dialogs_list.py --dialogs_limit -1`
5. `python 1_download_dialogs_data.py --dialogs_ids -1 --dialog_msg_limit -1`
6. Run cells in `HW3/telegram-dialogs-analysis-v2/0_merge_data.ipynb`
7. Run cells in `HW3/telegram-dialogs-analysis-v2/1_data_review.ipynb`

# Homework 4
1. Load dataset by Kate Burovova to the `./data` (wrt. this `README.md`)
2. Run cells in `./HW4/4_markiian_mandzak.ipynb`

# Homework 5
0. The personal data should already be loaded to `./data_personal`. If not - go through steps 0 to 5 from section `Homework 3`
1. Run cells in `./HW5/5_markiian_mandzak.ipynb`                                          