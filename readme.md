## 순서
- github의 repo에서 Setting > Archives에서 다음과 같이 설정한다.  
![](./Annotation_2020-09-01_010352.png)  
- 바이너리 파일을 lfs 사용으로 설정한다.  
여기서는 테스트기 때문에 용량은 작아도 바이너리인 png파일을 lfs로 설정한다.  
`$ git lfs track "*.png"`  
- 깃 히스토리에서 png파일의 내용대신 링크로 보이는것을 확인 할 수 있다.  
![](./git-history.png)  
