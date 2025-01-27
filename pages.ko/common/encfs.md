# encfs

> 암호화된 가상 파일 시스템을 마운트하거나 생성.
> 마운트된 파일 시스템을 마운트 해제할 수 있는 `fusermount`도 참조.
> 더 많은 정보: <https://github.com/vgough/encfs>.

- 암호화된 파일 시스템 초기화 또는 마운트:

`encfs {{/경로/대상/암호화_폴더}} {{/경로/대상/마운트_지점}}`

- 표준 설정으로 암호화된 파일 시스템을 초기화:

`encfs --standard {{/경로/대상/암호화_폴더}} {{/경로/대상/마운트_지점}}`

- 데몬을 생성하는 대신 포어그라운드에서 encfs를 실행:

`encfs -f {{/경로/대상/암호화_폴더}} {{/경로/대상/마운트_지점}}`

- 일반 디렉터리의 암호화된 스냅샷을 마운트:

`encfs --reverse {{경로/대상/일반_디렉토리}} {{경로/대상/암호화_폴더}}`
