import requests 

url = "http://www.example.com/proxylist.txt" 

# Get the list of proxies from the URL 
r = requests.get(url) 

# Split the response into separate lines 
lines = r.text.split("

") 

# Open the proxy_list.txt file 
with open("proxy_list.txt", "w") as f: 
  # Write each line of the response to the file 
  for line in lines: 
    f.write(line + "

") 

# Print a success message 
print("Proxy list successfully updated!") 
