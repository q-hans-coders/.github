

## “local-dream” by xororz, [GitHub](https://github.com/xororz/local-dream), Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.ko)
<br/>
<br/>

# 1. Project Overview (프로젝트 개요)
ZOO: Zero One Organisms
"Zero One"은 디지털 세계에서 자주 사용되는 개념으로, 
0과 1로 이루어진 디지털 동물들이 창조되는 곳이라는 메시지를 담을 수 있어요.

<br/>
<br/>

# 2. Team Members (팀원 및 팀 소개)
| 신유빈 | 박채연 | 신현수 | 송범록 |
|:------:|:------:|:------:|:------:|
| <img src="https://github.com/user-attachments/assets/5d7564a9-d246-4e71-9f53-d6f0f711282d" alt="신유빈" width="150"> | <img src="https://github.com/user-attachments/assets/6f2cf3aa-ba91-4888-bf84-76a1bb1204a3" alt="박채" width="150"> | <img src="https://github.com/user-attachments/assets/6cf6ae49-e37d-4dcc-a2d9-8602e51c83e2" alt="신현수" width="150"> | <img src="https://github.com/user-attachments/assets/6db1bcb8-b7d1-4142-aee7-6c8b8ef7aa72" alt="송범록" width="150"> |
| FE | TL | AI | AI |
| [GitHub](https://github.com/ubin-shin) | [GitHub](https://github.com/Bigdatabomb) | [GitHub](https://github.com/shinhyun-soo) | [GitHub](https://github.com/BeomRok) |

# 3. 판넬

![Image](https://github.com/user-attachments/assets/36b56eb5-a31e-454c-bf9c-4f7f0115523b)


---

## 주요 기능
- **음성 프롬프트 생성**  
  Whisper 기반 음성 인식을 통해 사용자의 설명을 AI 프롬프트로 자동 변환
- **AI 이미지 생성 & Inpainting**  
  Stable Diffusion V2.1을 활용해 원본 스케치 보완 및 고해상도 디지털 아트워크 생성
- **AR 시각화**  
  ARCore를 통해 생성된 동물을 실제 공간에 배치하여 증강현실 경험 제공
- **3D 프린터 출력 지원**  
  AR 모델을 3D 프린터용 파일(STL)로 내보내어 실물 인형 제작 가능
- **온디바이스 처리**  
  Qualcomm QNN SDK 및 Snapdragon 8 Elite 칩셋 기반으로 모든 AI 연산을 디바이스 내에서 수행하여 데이터 보안성과 오프라인 접근성 확보

---

## 기술 스택

| 구분       | 세부 항목                                                                                                    |
|------------|--------------------------------------------------------------------------------------------------------------|
| **플랫폼** | Android                                                                                                      |
| **칩셋**   | Qualcomm Snapdragon 8 Elite                                                                                  |
| **개발 언어** | Kotlin, C++, Rust, Python                                                                                  |
| **개발 도구** | Android Studio, CMake, Git                                                                                 |
| **프레임워크/SDK** | ARCore, QNN SDK, local-dream (by xororz, CC BY-NC 4.0)                                                   |
| **라이브러리** | Stable Diffusion V2.1, Whisper, tokenizer-cpp                                                             |

---

## 설치 및 실행

1. 레포지토리 클론  
   ```bash
   git clone https://github.com/q-hans-coders/test.git
   cd test


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
