# PRISMA 2020 Flow Diagram Generator — Claude Skill

문헌고찰을 위한 PRISMA 2020 flow diagram을 Claude 안에서 바로 만들어주는 스킬입니다. 코딩 없이, 대화창에 나타나는 입력 폼에 선별 단계별 숫자만 입력하면 고해상도 PNG와 Word 문서를 받을 수 있습니다.

License: MIT · PRISMA 2020 DOI: [10.1136/bmj.n71](https://doi.org/10.1136/bmj.n71)

## 주요 기능

- **인터랙티브 입력 폼** — 데이터베이스 선택(PubMed, CINAHL, Embase, PsycINFO, Web of Science, Cochrane Library, RISS, KISS, KoreaMed 또는 직접 추가) 후 검색 건수 입력
- **자동 계산** — Records screened, Reports sought, Reports assessed, Studies included가 자동으로 계산되어 산술 오류 방지
- **Registers 지원** — ClinicalTrials.gov, CRIS 등 임상시험 등록부 검색 건수를 별도 항목으로 입력하면 PRISMA 2020 양식에 맞추어 표시
- **수기검색 지원** — 수기검색(웹사이트, 기관, 인용 검색, 직접 추가) 입력이 있을 때만 "Identification of studies via other methods" 열이 표시
- **제외 사유 입력** — 전문 검토 제외 사유를 개수 제한 없이 추가하고 레이블 수정 가능
- **적응형 레이아웃** — 데이터베이스가 늘어나면 박스와 Identification 밴드가 함께 확장되어 공식 양식의 비율을 유지

## 설치 및 사용 방법

1. [PRISMA_flow_diagram_generator.skill 다운로드](https://github.com/rnrnrnn1234/prisma-2020-flow-diagram-claude-skill/raw/main/PRISMA_flow_diagram_generator.skill)
2. Claude.ai → 대화창 "+" 클릭 → 스킬 관리 클릭 → "추가" 클릭 → "스킬 업로드" 클릭 → 다운로드 받은 스킬 업로드
3. 대화창에 "+" 클릭 후 스킬 선택 — 입력 폼이 나타남
4. 검색한 데이터베이스를 체크하고 각각의 검색 건수 입력
5. 중복 제거 수와 제목/초록 제외 수 입력 — 나머지는 자동 계산
6. 전문 검토 제외 사유와 건수 입력
7. 요약 확인 후 "승인하고 생성" 클릭 → PNG와 Word 파일 다운로드

## 인용 및 출처

연구에 이 도구를 사용하셨다면 PRISMA 2020 원 논문을 인용해 주세요:

Page MJ, McKenzie JE, Bossuyt PM, Boutron I, Hoffmann TC, Mulrow CD, et al. The PRISMA 2020 statement: an updated guideline for reporting systematic reviews. BMJ 2021;372:n71. doi: [10.1136/bmj.n71](https://doi.org/10.1136/bmj.n71)

PRISMA 2020 흐름도 양식은 [PRISMA statement](https://www.prisma-statement.org/)가 [크리에이티브 커먼즈 저작자표시(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) 라이선스로 배포하며, 원 저작물을 올바르게 인용하는 조건으로 배포·수정·활용이 허용됩니다. 이 도구는 해당 양식을 기반으로 한 독립 구현물이며 PRISMA 그룹의 공식 승인을 받은 것은 아닙니다.

## 라이선스

- 소스 코드: MIT License © 2026 Soyeon Park
- PRISMA 2020 흐름도 양식 디자인: © PRISMA, CC BY 4.0

## 제작자

**박소연 (Soyeon Park)** — 서울대학교 간호대학 박사과정

rnsy1029@snu.ac.kr

## 지도교수

**우경미 (Kyungmi Woo)** — 서울대학교 간호대학 부교수

ANDA Lab: https://andalab.snu.ac.kr/

## 감사의 말

이 도구는 AI 도구(Claude, Anthropic)를 활용하여 개발되었습니다. 모든 설계 결정, 요구사항 정의 및 검증은 제작자가 수행했습니다.

---

# PRISMA 2020 Flow Diagram Generator — Claude Skill (English)

A Claude skill that generates PRISMA 2020 flow diagrams for systematic reviews directly inside your conversation. No coding required — enter your screening numbers in the input form that appears in the chat, and download a high-resolution PNG and a Word document.

## Features

- **Interactive input form** — select databases (PubMed, CINAHL, Embase, PsycINFO, Web of Science, Cochrane Library, RISS, KISS, KoreaMed, or add your own) and enter record counts
- **Automatic calculation** — records screened, reports sought, reports assessed, and studies included are computed automatically to prevent arithmetic errors
- **Registers support** — records from trial registries (ClinicalTrials.gov, CRIS, etc.) are entered separately and rendered per the PRISMA 2020 template
- **Hand-searching support** — the "Identification of studies via other methods" column appears only when other-methods sources (websites, organisations, citation searching, custom entries) are entered
- **Unlimited exclusion reasons** — add full-text exclusion reasons without limits and rename their labels
- **Adaptive layout** — the database box and the Identification band expand together as more databases are added, preserving the proportions of the official template

## Installation & Usage

1. [Download PRISMA_flow_diagram_generator.skill](https://github.com/rnrnrnn1234/prisma-2020-flow-diagram-claude-skill/raw/main/PRISMA_flow_diagram_generator.skill)
2. In Claude.ai, click "+" in the chat box → Manage skills → Add → Upload skill → upload the downloaded file
3. Click "+" in the chat box and select the skill — the input form appears
4. Check the databases you searched and enter the number of records for each
5. Enter the number of duplicates removed and records excluded by title/abstract — the rest is calculated automatically
6. Add full-text exclusion reasons with their counts
7. Review the summary and click "Approve and generate" → download the PNG and Word files

## Citation & Attribution

If you use this tool in your research, please cite the original PRISMA 2020 publication:

Page MJ, McKenzie JE, Bossuyt PM, Boutron I, Hoffmann TC, Mulrow CD, et al. The PRISMA 2020 statement: an updated guideline for reporting systematic reviews. BMJ 2021;372:n71. doi: [10.1136/bmj.n71](https://doi.org/10.1136/bmj.n71)

The PRISMA 2020 flow diagram template is distributed by the [PRISMA statement](https://www.prisma-statement.org/) under the [Creative Commons Attribution (CC BY 4.0) license](https://creativecommons.org/licenses/by/4.0/), which permits others to distribute, remix, adapt and build upon the work, provided the original work is properly cited. This tool is an independent implementation built upon that template and is not officially endorsed by the PRISMA group.

## License

- Source code: MIT License © 2026 Soyeon Park
- PRISMA 2020 flow diagram template design: © PRISMA, CC BY 4.0

## Author

**Soyeon Park (박소연)** — Doctoral Student, College of Nursing, Seoul National University

rnsy1029@snu.ac.kr

## Advisor

**Kyungmi Woo (우경미)** — Associate Professor, College of Nursing, Seoul National University

ANDA Lab: https://andalab.snu.ac.kr/

## Acknowledgements

Developed with the assistance of AI tools (Claude, Anthropic). All design decisions, requirements, and validation were performed by the author.
