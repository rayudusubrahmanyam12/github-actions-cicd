# Topics
1) Self Hosted Runners
2) Github Hosted Runners
3) Secrets
4) 


# Acrions Settings

Actions permissions

. Any action or reusable workflow can be used, regardless of who authored it or where it is defined.

. The Actions tab is hidden and no workflows can run.

. Any action or reusable workflow defined in a repository within rayudusubrahmanyam12 can be used.

. Any action or reusable workflow that matches the specified criteria, plus those defined in a repository within rayudusubrahmanyam12, can be used. Learn more about allowing specific actions and reusable workflows to run.

# Artifact and log retention
Choose the repository settings for artifacts and logs.
Artifact and log retention
90    days
Your organization has set a maximum limit of 90 days. 


# Runners
Runners available to this repository
GitHub-hosted runners                               Self-hosted runners
Larger GitHub-hosted runners    New
    Team & Enterprise
    Sizes up to: 64-cores · 256 GB RAM · 2040 GB SSD Storage · Windows, Linux, and Mac
Standard GitHub-hosted runners
    Ready-to-use runners managed by GitHub. Learn more about GitHub-hosted runners.

# Self Hosted Runners

Download
# Create a folder
$ mkdir actions-runner && cd actions-runner

# Download the latest runner package
$ curl -o actions-runner-linux-x64-2.311.0.tar.gz -L https://github.com/actions/runner/releases/download/v2.311.0/actions-runner-linux-x64-2.311.0.tar.gz

# Optional: Validate the hash
$ echo "29fc8cf2dab4c195bb147384e7e2c94cfd4d4022c793b346a6175435265aa278  actions-runner-linux-x64-2.311.0.tar.gz" | shasum -a 256 -c

# Extract the installer

$ tar xzf ./actions-runner-linux-x64-2.311.0.tar.gz
Configure
# Create the runner and start the configuration experience
$ ./config.sh --url https://github.com/rayudusubrahmanyam12/github-actions-cicd --token <> 
# Last step, run it!
$ ./run.sh
Using your self-hosted runner
# Use this YAML in your workflow file for each job
runs-on: self-hosted


rpm -q libicu
yum install libicu -y
rpm -q libicu


 sudo yum update -y && \
 sudo yum install docker -y && \
 sudo yum install git -y && \
 sudo yum install libicu -y && \
 sudo systemctl enable docker