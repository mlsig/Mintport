go here: https://github.com/nathanielkam/mint-csv-import
download code as zip, then unzip
make sure the mint-import... folder is in your documents folder
download Anaconda from here: https://www.anaconda.com/products/individual
Click "run cmd" in anaconda
type "cd Documents" and click enter
type "cd mint" then press tab, then enter.
type "pip3 install -r requirements.txt" and press enter
edit import.csv with your transactions
log into mint on chrome
create 1 manual test transation, dont submit it yet
click Cntrl+Shift+I
click the Network tab
submit the transaction
find "updateTransaction.xevent" (must be exact, you may see similar)
right click > copy > copy as cmd
paste that into a document somewhere
open the import.py file in notepad
find the required variables and set them* this is tough to navigate through.
save that .py file
you can now delete that test transation and the thing you copy pasted eariler
back in anaconda, type "python import.py' and click enter.


to do this again:
edit import.csv with your transactions
Click "run cmd" in anaconda
type "cd Documents" and click enter
type "cd mint" then press tab, then enter.
type "python import.py' and click enter.