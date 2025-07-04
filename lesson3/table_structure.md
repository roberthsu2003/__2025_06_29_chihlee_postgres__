# 學生資料表
## table name: students
## 資料表結構
| 欄位名稱       | 資料型態   | 主鍵 | 必填 | 預設值 | 說明         |
| ---- | ---- |--- | ---- | ---- | ---- |
| student_id | SERIAL  | Y  | Y   |    | 學生id，唯一識別學生 |
| name | VARCHAR(20) |  N | Y  |  N  | 學生姓名 |
| major | VARCHAR(20) | N  | Y   |  N  | 學生年齡 |

## sql 語法
```sql
CREATE TABLE students (
    student_id SERIAL PRIMARY KEY,
    name VARCHAR(20) NOT NULL,
    major VARCHAR(20) NOT NULL
);
```
