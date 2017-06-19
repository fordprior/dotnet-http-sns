# dotnet-http-sns
Dotnet app that builds in CircleCI and publishes to AWS SNS.

# steps
1. launch an linux AMI t2.micro instance on aws free tier
2. install WinSCP, convert your.pem to a .ppk, and launch your PuTTY CLI & WinSCP file manager
3. SSH into the instance and start doing stuff:
* install .NET core using CentOS instructions (https://www.microsoft.com/net/core#linuxcentos)
* install git and run `git clone https://github.com/fordprior/dotnet-http-sns`
4. execute `dotnet restore`, `dotnet build`, and `dotnet run` to see Snagajob's public repos
5. log into circleCI and build project


