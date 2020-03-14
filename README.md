# Python_Applications

The Python Notebook helps in collecting 1 month data per Symbol.

The Application requires the Yaml file, 'Input_for_NSE.Yaml', for all it's input needs.

The Yaml File carries 4 inputs,

Date:It's a String. the Date upto which you want your data, Eg. if you want past 10 days of data till date(14/03/2020), then Date == 14/03/2020

No_of_days_data: it's a Integer. How many days data you require.

Output_Src_Data: it's a path in String format. Used to store the unzipped CSVs for each day

Output_Final_Data: it's a path in String format. It is used to store the CSV for each symbol for 'No_of_days_data' readings/
