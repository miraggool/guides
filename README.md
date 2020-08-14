# Anaconda
https://www.anaconda.com/products/individual   
1. 가상환경 리스트 확인
<pre>
conda info --envs
</pre>
2. 가상환경 생성
<pre>
conda create --name "가상환경명" python=버전
</pre>
3. 가상환경 삭제
<pre>
conda remove --name "가상환경명" --all 
</pre>
4. 가상환경 활성화
<pre>
activate "가상환경명"
</pre>
5. 가상환경 내 설치된 모듈 리스트 확인
<pre>
conda list 
</pre>
6. 가상환경 내 캐시 삭제
<pre>
conda clean --all
</pre>
7. 업데이트
<pre>
conda update conda
</pre>

