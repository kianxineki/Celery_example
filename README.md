Celery_example
==============

Example of using celery with sqlite3

Tutorial:

1. Install celery and rabbitmq

2. start rabbitmq

3. create db (python create_db.py)

4. start celery (celery worker -A tasks)

5. insert task (python launch_task.py)

6. view result (python view_result.py id_return_launch_task)
