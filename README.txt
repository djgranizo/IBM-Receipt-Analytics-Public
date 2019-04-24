Georgia Tech Undergraduate Consulting Club
IBM Receipt Analytics Team

Diego Granizo		Team Lead	djgranizo@gmail.com	
Dongsuk (David) Lim	Team Lead	dlim46@gatech.edu	
Soobin Baek		Analyst		soobin1012@yahoo.co.uk	
Kunal Sharma		Analyst		ksharma74@gatech.edu	
Nicole Fran Wang	Analyst		nicolefranwang@gmail.com	

Regarding use of this Repository

Directory Structure
/img: directory of receipt images with OCR results overlayed for debugging and developping
/json: directory of json output from Azure OCR. These files are used in the total extraction
/metrics: Contains CSV, Excel of best receipts for analysis and results
/text: directory of cleaned text files containing on only word information used in Date and Expense Type

Note: 
OCR Capabilities have expired and new OCR keys need to be generated but for testing and demonstration approx 168 receipts have been processed

Final Algorithm.ipynb requires the directory structure outlined above to store and read OCR Output
See jupyter notebook for documentation on each function and the final pipeline