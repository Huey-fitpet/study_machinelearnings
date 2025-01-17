| 컬럼명            | 데이터 타입 | 데이터 분류 | 결측치 | 사용여부 | Unique | 요약                     |
|------------------|-------------|--------------|--------|----------|--------|--------------------------|
| ID               | int64      |              | X      |          |        | ID                       |
| Gender           | object     | 범주         | 0      | O        | 2      | 성별                     |
| Ever_Married     | object     | 범주         | 140    | O        | 2      | 결혼 유무                |
| Age              | int64      | 연속         | 0      | O        | 67     | 나이                     |
| Graduated        | object     | 범주         | 78     | O        | 2      | 졸업 유무                |
| Profession       | object     | 범주         | 124    | X        | 9      | 직군                     |
| Work_Experience   | float64    | 범주         | 829    | O        | 15     | 연차                     |
| Spending_Score   | object     | 범주         | 0      | O        | 3      | 지출 점수                |
| Family_Size      | float64    | 범주         | 335    | O        | 9      | 가족 수                  |
| Var_1            | object     | 범주         | 76     | X        | 7      | 숨김 분류                |
| Segmentation     | object     | 범주         | 0      | X        | 4      | 분류 결과 (label)       |