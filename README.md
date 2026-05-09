#!/bin/bash


echo "Enter your name:"
read name

echo "Enter a folder name:"
read folderName

mkdir "$folderName"
cd "$folderName" 

echo "Open-Source Technologies." > readme.txt
echo "Hello, $name! Your folder '$folderName' has been successfully created!"
