# Cheatsheet
my uber l33t haxxing cheatsheet

# Conda
conda install <package> ¦ install some packeage
conda env export > exportfile.yaml ¦ export environment to a file
  
# bash
ls  ¦ show current folder content

ls -a ¦ include hidden files (.hidden)

cd change directory
cd ~ ¦ change to home 
pwd ¦ show current working directory
echo "Text" ¦ prints text to the command line
echo "$variable" ¦ prints a variable's value to the command line
read variable ¦ read user input and store it as variable
while [  True ]; do 
done ¦  while loop
if [ "$choice" = 1 ]; then
elif [ "$choice" = 2 ]; then
else
fi ¦ if loop


# ML Pipeline
my basic data science / ML workflow. 

read data
get (visual) overview
separate categorrical / numeric
scale numeric, hotEncode categorical
impute (create missing data)
make polynomeFeatures
fit linear model
make R2, score, cv score, ....

plot KPIs, like scores, coefficients versus iterations, parameters

make conclusions/ select features
repeat

