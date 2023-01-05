#     Create source code, upload to github.com
#     Use Django, DjangoRestFramework
#     Implement JWT authentication plugin
#     Has 1 middleware to log to a file: total time to process a request/response
#     Has an app
#     Connect to 2 database (postgresql/mariadb/mysql) run in replication mode (1 master, 1 slave)
#         create a db-router to write only to master database
#                               read only from slave database
#     Deploy with Gunicorn (3 concurrent workers)