# crawl-scoop-directory
爬取https://rasa.github.io/scoop-directory/by-score, 生成一个SQLite数据库.

详情见: https://github.com/rasa/scoop-directory/issues/19

配置了GitHub Actions, 每12小时自动生成数据库文件到该Repository.

|                文件                |     说明      |
| ---------------------------------- | ------------- |
| scoop_directory_crawler.py         | 爬虫脚本      |
| scoop_directory.db                 | 数据库文件     |
| scoop_search.py、find-scoopApp.ps1 | 数据库查询脚本 |

其中数据库查询脚本已做成Web API, 代码见: https://github.com/zhoujin7/scoop-search
