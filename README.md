# 에너지 수요 예측 프로젝트

**대회**: [Enefit - Predict Energy Behavior of Prosumers](https://www.kaggle.com/competitions/predict-energy-behavior-of-prosumers)


### 1. 데이터 다운로드
Kaggle 대회 페이지에서 데이터를 다운로드하여 `data/` 폴더에 압축해제

**필수 데이터 파일들:**
- `train.csv`
- `client.csv`
- `electricity_prices.csv`
- `gas_prices.csv`
- `historical_weather.csv`
- `forecast_weather.csv`
- `weather_station_to_county_mapping.csv`
- `county_id_to_name_map.json`

### 2. 노트북 실행 순서
1. **EDA.ipynb** 
2. **Preprocess.ipynb** 
3. **LinearReg.ipynb** - 베이스라인 모델 (Linear Regression)
4. **XGBoost.ipynb** - 개선된 모델 (XGBoost)

##  모델 성능

| 모델 | MAE | 개선율 |
|------|-----|--------|
| Linear Regression | 46.46 | - |
| **XGBoost** | **37.44** | **+19.41%** |


## 노트

- 모든 노트북은 `data/` 폴더를 기준으로 경로가 설정되어 있습니다.
- 전처리된 데이터는 `data/processed_data/`에 저장됩니다.
