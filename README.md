# Creating your first project

## Requirements

Git&#x20;

a web browser

a terminal ( here it's an ubuntu terminal but you can use any which supports git )

## Creating a project

### Initialize git

Open your comman prompt. And type <mark style="color:yellow;">**`git init`**</mark> . This initializes a git repository or more specifically a `.git` folder which contains `blobs` `commits` and everything else **you need not worry about**.

### **Create a sample file**

Lets create a sample Readme file called `README.md` .

```
<![CDATA[
# ${1:Project Name}
TODO: Write a project description
## Installation
TODO: Describe the installation process
## Usage
TODO: Write usage instructions
## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
## History
TODO: Write history
## Credits
TODO: Write credits
## License
TODO: Write license
]]>
```

### Commiting the file

First we have to add the file with <mark style="color:yellow;">**`git add .`**</mark>  this adds all files previously not identified by git.

Now if you don't encounter any errors type <mark style="color:yellow;">**`git commit -m "`**</mark><mark style="color:green;">**`A sample message`**</mark><mark style="color:yellow;">**`"`**</mark> .  &#x20;

you can replace <mark style="color:green;">**A sample message**</mark> with anything you want to identify with it.



### Pushing the file

Push the file with <mark style="color:yellow;">**`git --set-upstream https://git.krios.studio/`**</mark><mark style="color:purple;">**`USERNAME`**</mark><mark style="color:yellow;">**`/`**</mark><mark style="color:purple;">**`REPOSITORY-NAME`**</mark>**`  `**<mark style="color:yellow;">**``**</mark>**`  `**<mark style="color:purple;">**`BRANCH`**</mark> .

Replace <mark style="color:purple;">**`USERNAME`**</mark> <mark style="color:purple;">**`REPOSITORY-NAME`**</mark> and <mark style="color:purple;">**`BRANCH`**</mark> with your username , reository name and branch respectively

{% hint style="warning" %}
&#x20;The above command should only be done for the first push . After that just use

<mark style="color:yellow;">**`git push https://git.krios.studio/`**</mark><mark style="color:purple;">**`username`**</mark><mark style="color:yellow;">**`/`**</mark><mark style="color:purple;">**`repository-name`**</mark> .
{% endhint %}
