# radare2

> 리버스 엔지니어링 도구 세트.
> 더 많은 정보: <https://www.radare.org/r/docs.html>.

- 파일 형식 헤더를 파싱하지 않고 쓰기 모드로 파일 열기:

`radare2 -nw {{경로/대상/바이너리}}`

- 프로그램 디버깅:

`radare2 -d {{경로/대상/바이너리}}`

- 대화형 CLI에 들어가기 전에 스크립트 실행:

`radare2 -i {{경로/대상/스크립트.r2}} {{경로/대상/바이너리}}`

- 대화형 CLI에서 명령어에 대한 도움말 표시:

`{{radare2_명령어}}?`

- 대화형 CLI에서 셀 명령어 실행:

`!{{셸_명령어}}`

- 현재 블록의 원시 바이트를 파일로 덤프:

`> pr > {{경로/대상/파일.bin}}`
