# STRUCTURE · kurodacoffee-sample

```
kurodacoffee-sample/
├─ index.html              단일 파일 (CSS·JS 인라인)
├─ wrangler.toml           name = kurodacoffee-sample → kurodacoffee-sample.lgt3232.workers.dev
├─ .assetsignore           img/·문서·index_*.html·미사용 webp 3개 배포 제외
├─ kc-dela.woff2           일본어 간판 (Dela Gothic One)
├─ kc-blackhan.woff2       한글 간판 (Black Han Sans)
├─ kc-zenantique.woff2     일본어 메뉴·라벨 (Zen Antique)
├─ kc-gowun-400/700.woff2  한글 본문 (Gowun Batang)
├─ kc-logo.webp            로고 일러스트 (먹색, 파비콘·인사말)
├─ kc-logo-cream.webp      로고 일러스트 (크림색, 헤더·푸터)
├─ kc-*.webp               메뉴 사진 (히어로 아이스커피·토스트·인기 메뉴 6)
├─ og-kuroda.jpg           공유 썸네일 1200×630
├─ img/                    다올 제공 원본 (배포 제외)
├─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더(원목 간판, 스티키) → `#top` 히어로 + 원형 배지 → `#about` 인사말 → `#morning` 모닝세트(깅엄) → 인기 메뉴(벨벳) → `#menu` 메뉴판(お品書き) → `#visit` 오시는 길 → 푸터.

## 메뉴 수정
메뉴판은 `.cat > .item` 반복. 가격·이름 바꾸면 폰트 서브셋 재생성 필요(새 글자일 때).
