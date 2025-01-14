| 컬럼명            | 데이터 타입 | 데이터 분류 | 결측치 | 이상치 | Unique | 요약 | 설명                                                         |
|------------------|-------------|--------------|--------|--------|--------|------|------------------------------------------------------------|
| Id               | int64      |              | 0      |        |        |      |                                                            |
| MSSubClass       | int64      | 연속형       | 0      |        |        |      | 건물 클래스                                                  |
| MSZoning         | object     | 범주형       | 0      |        | 5      |      | 일반 구역 분류                                              |
| LotFrontage      | float64    | 연속형       | 259    |        |        |      | 부동산에 연결된 도로의 선형 피트 수                           |
| LotArea          | int64      | 연속형       | 0      |        |        |      | 토지 면적 (제곱피트)                                        |
| Street           | object     | 범주형       | 0      |        | 2      |      | 도로 접근 유형                                              |
| Alley            | object     | 범주형       | 1369   |        | 2      |      | 골목 접근 유형                                              |
| LotShape         | object     | 범주형       | 0      |        | 4      |      | 부동산의 일반적인 형태                                       |
| LandContour      | object     | 범주형       | 0      |        | 4      |      | 부동산의 평탄함                                             |
| Utilities        | object     | 범주형       | 0      |        | 2      |      | 사용 가능한 유틸리티 유형                                    |
| LotConfig        | object     | 범주형       | 0      |        | 5      |      | 토지 구성                                                  |
| LandSlope        | object     | 범주형       | 0      |        | 3      |      | 부동산의 경사                                               |
| Neighborhood     | object     | 범주형       | 0      |        | 25     |      | 에임스 시내의 물리적 위치                                   |
| Condition1       | object     | 범주형       | 0      |        | 9      |      | 주요 도로 또는 철도와의 근접성                               |
| Condition2       | object     | 범주형       | 0      |        | 8      |      | 두 번째 도로 또는 철도와의 근접성 (두 번째가 있는 경우)         |
| BldgType         | object     | 범주형       | 0      |        | 5      |      | 주거 유형                                                  |
| HouseStyle       | object     | 범주형       | 0      |        | 8      |      | 주거 스타일                                                |
| OverallQual      | int64      | 연속형       | 0      |        |        |      | 전체 자재 및 마감 품질                                      |
| OverallCond      | int64      | 연속형       | 0      |        |        |      | 전체 상태 등급                                             |
| YearBuilt        | int64      | 연속형       | 0      |        |        |      | 원래 건축 날짜                                             |
| YearRemodAdd     | int64      | 연속형       | 0      |        |        |      | 리모델링 날짜                                              |
| RoofStyle        | object     | 범주형       | 0      |        | 6      |      | 지붕 유형                                                  |
| RoofMatl         | object     | 범주형       | 0      |        | 8      |      | 지붕 자재                                                  |
| Exterior1st      | object     | 범주형       | 0      |        | 15     |      | 주택 외부 덮개                                             |
| Exterior2nd      | object     | 범주형       | 0      |        | 16     |      | 주택 외부 덮개 (여러 자재가 있는 경우)                        |
| MasVnrType       | object     | 범주형       | 872    |        | 3      |      | 벽돌 베니어 유형                                           |
| MasVnrArea       | float64    | 연속형       | 8      |        |        |      | 벽돌 베니어 면적 (제곱피트)                                 |
| ExterQual        | object     | 범주형       | 0      |        | 4      |      | 외부 자재 품질                                            |
| ExterCond        | object     | 범주형       | 0      |        | 5      |      | 외부 자재의 현재 상태                                      |
| Foundation       | object     | 범주형       | 0      |        | 6      |      | 기초 유형                                                  |
| BsmtQual         | object     | 범주형       | 37     |        | 4      |      | 지하실 높이                                                |
| BsmtCond         | object     | 범주형       | 37     |        | 4      |      | 지하실의 일반적인 상태                                      |
| BsmtExposure      | object     | 범주형       | 38     |        | 4      |      | 출입구 또는 정원 수준의 지하실 벽                           |
| BsmtFinType1     | object     | 범주형       | 37     |        | 6      |      | 지하실 마감 면적 품질                                      |
| BsmtFinSF1       | int64      | 연속형       | 0      |        |        |      | 유형 1 마감 면적 (제곱피트)                                 |
| BsmtFinType2     | object     | 범주형       | 38     |        | 6      |      | 두 번째 마감 면적 품질 (존재하는 경우)                       |
| BsmtFinSF2       | int64      | 연속형       | 0      |        |        |      | 유형 2 마감 면적 (제곱피트)                                 |
| BsmtUnfSF        | int64      | 연속형       | 0      |        |        |      | 지하실 미완성 면적 (제곱피트)                               |
| TotalBsmtSF      | int64      | 연속형       | 0      |        |        |      | 지하실 총 면적 (제곱피트)                                   |
| Heating           | object     | 범주형       | 0      |        | 6      |      | 난방 유형                                                  |
| HeatingQC         | object     | 범주형       | 0      |        | 5      |      | 난방 품질 및 상태                                          |
| CentralAir        | object     | 범주형       | 0      |        | 2      |      | 중앙 에어컨                                                |
| Electrical        | object     | 범주형       | 1      |        | 5      |      | 전기 시스템                                                |
| 1stFlrSF         | int64      | 연속형       | 0      |        |        |      | 1층 면적 (제곱피트)                                        |
| 2ndFlrSF         | int64      | 연속형       | 0      |        |        |      | 2층 면적 (제곱피트)                                        |
| LowQualFinSF     | int64      | 연속형       | 0      |        |        |      | 저품질 마감 면적 (모든 층)                                  |
| GrLivArea        | int64      | 연속형       | 0      |        |        |      | 지상 생활 면적 (제곱피트)                                   |
| BsmtFullBath     | int64      | 연속형       | 0      |        |        |      | 지하실 풀 욕실 수                                          |
| BsmtHalfBath     | int64      | 연속형       | 0      |        |        |      | 지하실 반 욕실 수                                          |
| FullBath         | int64      | 연속형       | 0      |        |        |      | 지상 풀 욕실 수                                           |
| HalfBath         | int64      | 연속형       | 0      |        |        |      | 지상 반 욕실 수                                           |
| BedroomAbvGr     | int64      | 연속형       | 0      |        |        |      | 지하실 위의 침실 수                                        |
| KitchenAbvGr     | int64      | 연속형       | 0      |        |        |      | 주방 수                                                    |
| KitchenQual      | object     | 범주형       | 0      |        | 4      |      | 주방 품질                                                  |
| TotRmsAbvGrd    | int64      | 연속형       | 0      |        |        |      | 지상 위의 총 방 수 (욕실 제외)                             |
| Functional       | object     | 범주형       | 0      |        | 7      |      | 주택 기능성 등급                                          |
| Fireplaces       | int64      | 연속형       | 0      |        |        |      | 벽난로 수                                                 |
| FireplaceQu      | object     | 범주형       | 690    |        | 5      |      | 벽난로 품질                                               |
| GarageType       | object     | 범주형       | 81     |        | 6      |      | 차고 위치                                                 |
| GarageYrBlt      | float64    | 연속형       | 81     |        |        |      | 차고 건축 연도                                            |
| GarageFinish     | object     | 범주형       | 81     |        | 3      |      | 차고 내부 마감                                            |
| GarageCars       | int64      | 연속형       | 0      |        |        |      | 차고 크기 (차 용량)                                       |
| GarageArea       | int64      | 연속형       | 0      |        |        |      | 차고 면적 (제곱피트)                                      |
| GarageQual       | object     | 범주형       | 81     |        | 5      |      | 차고 품질                                                 |
| GarageCond       | object     | 범주형       | 81     |        | 5      |      | 차고 상태                                                 |
| PavedDrive       | object     | 범주형       | 0      |        | 3      |      | 포장된 진입로                                             |
| WoodDeckSF       | int64      | 연속형       | 0      |        |        |      | 목재 데크 면적 (제곱피트)                                  |
| OpenPorchSF      | int64      | 연속형       | 0      |        |        |      | 오픈 포치 면적 (제곱피트)                                  |
| EnclosedPorch    | int64      | 연속형       | 0      |        |        |      | 닫힌 포치 면적 (제곱피트)                                  |
| 3SsnPorch        | int64      | 연속형       | 0      |        |        |      | 3계절 포치 면적 (제곱피트)                                 |
| ScreenPorch      | int64      | 연속형       | 0      |        |        |      | 스크린 포치 면적 (제곱피트)                                |
| PoolArea         | int64      | 연속형       | 0      |        |        |      | 수영장 면적 (제곱피트)                                    |
| PoolQC           | object     | 범주형       | 1453   |        | 3      |      | 수영장 품질                                               |
| Fence            | object     | 범주형       | 1179   |        | 4      |      | 울타리 품질                                               |
| MiscFeature      | object     | 범주형       | 1406   |        | 4      |      | 기타 카테고리에서 다루지 않는 기타 기능                   |
| MiscVal          | int64      | 연속형       | 0      |        |        |      | 기타 기능의 가치 (달러)                                   |
| MoSold           | int64      | 연속형       | 0      |        |        |      | 판매된 월                                                |
| YrSold           | int64      | 연속형       | 0      |        |        |      | 판매된 연도                                              |
| SaleType         | object     | 범주형       | 0      |        | 9      |      | 판매 유형                                                |
| SaleCondition    | object     | 범주형       | 0      |        | 6      |      | 판매 조건                                                |
| SalePrice        | int64      | 연속형       | 0      |        |        |      | 부동산의 판매 가격 (달러) - 예측하려는 목표 변수                     |