---
layout: home
title: Ko-ATOMIC
permalink: /
---

Korean Commonsense Knowledge Grpah, Ko-ATOMIC (HCLT2022~)

## GitHub Link

Download on Github Pages: [https://github.com/jooinjang/Ko-ATOMIC](https://github.com/jooinjang/Ko-ATOMIC)

[![KoATOMIC](https://img.shields.io/badge/featured%20on-KoATOMIC-lightgrey.svg)](https://github.com/jooinjang/Ko-ATOMIC)

## What is Ko-ATOMIC?

Ko-ATOMIC은 [ATOMIC2020][1]을 기반으로 하는 일반 상식 기반의 한국어 지식 그래프입니다.

일반 상식 기반의 지식 그래프란, 대규모 코퍼스에 포함되어 있는 일반 상식을 그래프로 표현하는 구조화된 지식 표현 방법입니다. 대표적으로 지식 정보를 `If-Then` 관계로 표현하고, If-Then 그래프 구조를 통해 unseen relation을 추론하는 ATOMIC이 있습니다.

Ko-ATOMIC은 ATOMIC을 모티브로 하여, 아래의 두 가지 방법으로 일반 상식 기반의 한국어 지식 그래프를 구축합니다.

1. 기존 ATOMIC을 한국어로 번역
2. 일반 상식 추론 데이터셋을 활용하여 Triple을 생성

이 때, 번역은 NAVER Cloud Platform에서 제공하는 [Papago API][2]를 사용합니다. 그리고, Triple 생성에 사용될 일반 상식 추론 데이터셋으로는 [KommonGen 데이터셋][3]을 사용합니다.

추후, 완전한 형태의 KoATOMIC을 구축하기 이전에, 기존의 ATOMIC을 한국어로 번역한 버전을 ATOMIC_trans, KommonGen 데이터셋으로 Triple을 생성한 버전을 KommonGenKG라고 지칭합니다.

## License

This work is open sourced under the MIT License, Version 2.0.

Copyright 2022 Jaewook Lee.

[1]: https://allenai.org/data/atomic-2020
[2]: https://www.ncloud.com/product/aiService/papagoTranslation
[3]: https://github.com/nlpai-lab/KommonGen