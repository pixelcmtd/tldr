# complete

> 쉘 명령어에 자동 완성 인자를 제공합니다.
> 더 많은 정보: <https://www.gnu.org/software/bash/manual/html_node/Programmable-Completion-Builtins.html#index-complete>.

- 함수에 명령어 자동 완성 기능을 적용합니다:

`complete -F {{함수}} {{명령어}}`

- 다른 명령어에 명령어 자동 완성 기능을 적용합니다:

`complete -C {{자동완성_명령어}} {{명령어}}`

- 작성 완료된 단어에 공백을 추가하지 않고 자동 완성 기능을 적용합니다:

`complete -o nospace -F {{함수}} {{명령어}}`
