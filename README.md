이 프로젝트 코드는 ESP32 기반으로 동작하는 기상정보 기반 마이크로그리드 EMS 시스템입니다.
한국의 기상청 api를 활용하여 현재 위치의 기상정보를 기반으로 태양광 발전량을 예측하고 실제 발전량과 비교를 할 수 있습니다.
기상청 api를 통해 오늘, 내일, 모레의 발전량을 예측하고 내일 발전량에 따라 ESS의 모드를 결정하여 normal 또는 eco모드로 자동으로 전환됩니다.
////////////////////////////////////////////////////////////////

This project code is a weather information based microgrid EMS system that operates on ESP32.
Using the Korea Meteorological Administration API, it is possible to predict the amount of solar power based on the weather information of the current location and compare it with the actual amount of power generation.
Through the Korea Meteorological Administration api, the power generation of today, tomorrow, and the day after tomorrow is predicted, and the mode of ESS is determined according to the power generation of tomorrow, and it is automatically switched to normal or eco mode.
