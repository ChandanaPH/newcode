echo "enter the filename"
read name
if [-f $name]
then
echo "$name s file"
if [-d $name]
then
echo "$name is directory"
if [-l $name]
then
echo "$name is line"
else
echo "doesnot exist"
fi
