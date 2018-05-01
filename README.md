# bash-tutorials
Contains some simple scripts for coders looking to learn bash scripting.

## How to use:

### Download the Git repo
Go onto your chosen directory and run

<code>git clone https://github.com/ash-robinson/bash-tutorials.git</code>

### Run the Task

Open the task directory
<code>cd task-XXX</code>

Should contain a file structure with 3 files:
.
 * [README.md](./README-md)
 * [task-XXX](./task-XXX)
   * [answers.sh](./task-XXX/answers.sh)
   * [instruction.txt](./task-XXX/instruction.txt)
   * [task.sh](./task-XXX/task.sh)


### View Instructions

<code>cat instruction.txt</code>

### Run task.sh

#### Make Executable

<code>chmod +x task.sh</code>

#### Run it as root:

<code>./task.sh</code>

### Run answers.sh

#### Make Executable

<code>chmod +x answers.sh</code>

#### Run it as root:

<code>./answers.sh</code>

#### Example of how to use answers.sh
<code>echo "answer 1:  $(./task.sh my_answer)"</code>

