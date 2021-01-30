Tasks:

JSON:
{
  "puppet_task_version": 1,
  "supports_noop": false,
  "description": "Tech dev. PS Kill",
  "input_method": "environment",
  "parameters": {
    "PID": {
      "description": "The process ID to kill",
      "type": "Integer"
    }
  }
  {
  "implementations": [
    {"name": "pid_kill.sh", "requirements": ["shell"]},
    {"name": "pid_kill.ps1", "requirements": ["powershell"]}
    ]
  }
}

SH:
https://github.com/puppetlabs/tasks-hands-on-lab/blob/master/05-writing-tasks/README.md#write-your-first-task-in-bash


PS1:
