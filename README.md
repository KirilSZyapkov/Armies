# Armies

Write a function that stores information about an army leader and his armies. The input will be array of strings. The strings can be in some of the following formats: 
"{leader} arrives" – add the leader (no army) 
"{leader}: {army name}, {army count}" – add the army with its count to the leader (if he exists) 
"{army name} + {army count}" – if the army exists somewhere add the count 
"{leader} defeated" – delete the leader and his army (if he exists) 

When finished reading the input sort the leaders by total army count in descending. Then each army should be sorted by count in descending. 

Print in the following format: 
"{leader one name}: {total army count} 
>>> {armyOne name} - {army count} 
>>> {armyTwo name} - {army count} 
… 
{leader two name}: {total army count} 
…" 
