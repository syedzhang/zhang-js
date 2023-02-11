import os

# specify the directory containing your .js files
dir = '/path/to/js/files'

# create an empty string to store the contents of all the files
all_js = ''

# loop through each file in the directory
for filename in os.listdir(dir):
    # only process .js files
    if filename.endswith('.js'):
        with open(os.path.join(dir, filename), 'r') as f:
            # add the contents of the file to the all_js string
            all_js += f.read()

# write the contents of all_js to a new file
with open('all.js', 'w') as f:
    f.write(all_js)
