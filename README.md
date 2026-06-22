# MARL Policy Sharing Project

`simple_spread_v3`에서 shared policy와 independent policy를 비교하는 소규모 프로젝트이다.
코드는 `final-project.ipynb`에 모두 들어 있다.

## 실행

```bash
conda create -n marl-small python=3.11 -y
conda activate marl-small
pip install -r requirements.txt
jupyter notebook
```

이후 `final-project.ipynb`를 위에서부터 실행한다.
평가 영상은 `videos/shared`와 `videos/independent`에 저장된다.

빠른 실행 확인은 노트북에서 `FAST_RUN = True`로 변경하면 된다.
