# 급여뚝딱 개인정보처리방침 (GitHub Pages)

- 방침: https://loadguess-cyber.github.io/paypop-privacy/
- 계정 삭제 안내: https://loadguess-cyber.github.io/paypop-privacy/delete-account/

원본은 `payroll/privacy-policy-site-v2/index-sync.js` 다. 여기 파일을 직접 고치지 말고
원본을 고친 뒤 정적 파일로 다시 뽑아 올린다 (2026-10-18 chatgpt.site → GitHub Pages 이전).

다시 뽑기 (payroll 폴더에서):

    node privacy-policy-site-v2/export-gh.mjs privacy-policy-site-v2/index-sync.js privacy-policy-site-gh %TEMP%/p.mjs

그 다음 이 폴더에서 commit · push.
