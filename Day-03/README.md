☑𝐏𝐢𝐥𝐥𝐚𝐫𝐬 𝐎𝐟 𝐀𝐧𝐲 𝐏𝐫𝐨𝐠𝐫𝐚𝐦 --> keywords, data types, operators, logical reasoning 

☑𝐏𝐨𝐩𝐮𝐥𝐚𝐫 𝐊𝐞𝐲𝐰𝐨𝐫𝐝𝐬 𝐟𝐫𝐨𝐦 𝐃𝐞𝐯𝐎𝐩𝐬 𝐏𝐨𝐢𝐧𝐭 𝐎𝐟 𝐕𝐢𝐞𝐰 --> and, or, not, if, else, elif, while, for, in, try, except, finally, def, return, class, import, from, as, True, False, None, is, lambda, with, global, nonlocal, etc .

☑𝐕𝐚𝐫𝐢𝐚𝐛𝐥𝐞𝐬 --> Variables are used to store and manage data. They act as containers or placeholders for values, allowing you to manipulate and work with data in your programs.

☑𝐖𝐡𝐲 𝐔𝐬𝐞 𝐕𝐚𝐫𝐢𝐚𝐛𝐥𝐞𝐬? -->
👉Variables enable you to reuse the same value or result in multiple parts of your code. Instead of hardcoding values, using variables makes it easier to update and maintain your code.
Suppose, you have 1000 lines of code. and you have to use (let's say print) the name of your ec2 instance in line number 3, 38, 54, 76, 89, 98, 157, 200, 228, 294, 300, 330, 500, ..... 25 times and the name is "project-devops-sachin-1". 

print("project-devops-sachin-1") # write 25 times.
# Output: project-devops-sachin-1 #25 times

👉Otherwise, use a variable, assign the value "project-devops-sachin"; provide that variable to print().

# Assigning a value to a variable
ec2_instance = "project-devops-sachin-1"
# Accessing the value of a variable
print(ec2_instance)
# Output: project-devops-sachin-1 #25 times

☑Using variables in your code streamlines processes. Instead of writing redundant lines, you can modify values in one place, reducing the risk of errors and making debugging more efficient. For instance, if you need to update the name of an EC2 instance across 25 lines, using a variable allows for a single change, minimizing the chance of overlooking modifications needed. 
In summary, variables save time, enhance code readability, and mitigate errors during debugging and updates.

☑𝐆𝐥𝐨𝐛𝐚𝐥 𝐕𝐚𝐫𝐢𝐚𝐛𝐥𝐞𝐬 -->
y = 20 # Global variable
def another_function():
 print(y) # This will access the global variable 'y'
another_function()
print(y) # This will print 20

☑𝐋𝐨𝐜𝐚𝐥 𝐕𝐚𝐫𝐢𝐚𝐛𝐥𝐞𝐬 -->
def my_function():
 x = 10 # Local variable
 print(x)
my_function()
print(x) # error since 'x' is not defined outside the function. 

☑𝐍𝐚𝐦𝐢𝐧𝐠 𝐂𝐨𝐧𝐯𝐞𝐧𝐭𝐢𝐨𝐧𝐬 𝐨𝐟 𝐕𝐚𝐫𝐢𝐚𝐛𝐥𝐞𝐬
𝑺𝒏𝒂𝒌𝒆 𝑪𝒂𝒔𝒊𝒏𝒈 -->
ec2_instance_name

𝑪𝒂𝒎𝒆𝒍 𝑪𝒂𝒔𝒊𝒏𝒈 -->
ec2InstanceName
