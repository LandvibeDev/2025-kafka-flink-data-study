# 2025-kafka-flink-data-study
먼저 kafka-lab 파일 통째로 다운 받는 방법을 모르겠어서 폴더안에 있는 파일들을 각각 다운받아 바탕화면에 저장했습니다.

<img width="322" height="118" alt="스크린샷 2025-07-29 오전 8 58 48" src="https://github.com/user-attachments/assets/003fc1e3-d48a-40b0-b7d9-c68df471b481" />

이 명령어를 터미널에 입력했더니 zsh: command not found: brew 라는 오류 문구 -> 챗지피티한테 물어보니 Docker를 다운받아야 한다고 해서 링크 알려준대로 다운 받았습니다.
그리고나서 명령어를 다시 입력했더니 또 오류문구가 떠서 재질문

<img width="870" height="668" alt="스크린샷 2025-07-29 오전 9 02 44" src="https://github.com/user-attachments/assets/b8d8f0e4-098d-46d8-a6ca-bf09a4070074" />

알려준대로 복붙했더니 정상적으로 다운로드 완료

<img width="498" height="384" alt="스크린샷 2025-07-29 오전 9 05 11" src="https://github.com/user-attachments/assets/c9edd405-afae-4693-828d-dd3e3e758cc5" />

(사실 잘 되고 있는건지 잘 모르겠음)

<img width="728" height="371" alt="스크린샷 2025-07-29 오전 9 37 04" src="https://github.com/user-attachments/assets/022c4f5c-9c65-4e9e-b15a-4a8b16677067" />

바탕화면에 다운 받아놨던 docker-compose 파일로부터 잘 다운 받고 있는 듯?

<img width="710" height="329" alt="스크린샷 2025-07-29 오후 12 18 22" src="https://github.com/user-attachments/assets/0e56ed6e-89a4-4248-88c5-d969b7b7ee07" />

python 환경설정 해주기

<img width="732" height="181" alt="스크린샷 2025-07-29 오후 12 19 54" src="https://github.com/user-attachments/assets/09a3f542-3887-473c-9563-46953839967e" />

kafka 클러스터 시작 부분에서의 docker compose 실행

<img width="731" height="245" alt="스크린샷 2025-07-29 오후 12 21 59" src="https://github.com/user-attachments/assets/3bb2b9d7-df77-4622-95fa-cd7acfe8619c" />

user-singups 토픽을 3개의 파티션으로 생성

<img width="652" height="340" alt="스크린샷 2025-07-29 오후 12 24 17" src="https://github.com/user-attachments/assets/6a057e50-1b55-44ae-9415-eee01377d78f" />

수업 때 봤던대로 2초마다 새로운 사용자 가입 이벤트를 생성하여 Kafka 토픽으로 전송

<img width="1453" height="674" alt="스크린샷 2025-07-29 오후 12 25 04" src="https://github.com/user-attachments/assets/2874179a-dcb0-428d-9526-a6de1de20df6" />

잘 되는 것 같다



