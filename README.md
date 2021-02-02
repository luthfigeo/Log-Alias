# Log-Alias
Synchronize log alias to be a single mnemonic

Usually we deal with broad range of well log mnemonics, this brief codes (and bunch of log aliases) tried to uniform the log alias into one specific name. It also merge similar log type but has different mnemonic and interval within the same well. Further development should need a normalization for each log before the merging begin because different mnemonics might be due to different service company or tools in which the measurement could be different. These codes could be applied for single well or multi well.

**Input:**
A csv file consist of log measurements (and well name if you want to run multiwell), each column consist of one log. I recommend using lasio to read LAS file and convert it to dataframe, later you can save it as csv to be inputted in these code, or, you can directly use the dataframe as input.
