# project_monitor
监控系统，包含定时任务脚本等

```
git clone https://github.com/pureoym/project_monitor.git
```

```
0 8 * * 3 python /application/search/bin/find_error_task.py
0 0 2 * * python /application/search/bin/flow_control_copy/flow_control_copy.py
0 6 * * * python /application/search/urlImport.py
```
