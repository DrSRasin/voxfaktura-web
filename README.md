# voxfaktura-web

---

# ПРАВИЛО БОРЬБЫ С ХИМЕРАМИ — THE ANTI-CHIMERA RULE

**House Law, issued 2026-11-24 by Dr. Simon M. Rasin, Product Owner, MnemAxis.**
**Applies to every agent and every human producing code in this repository. No exceptions, no "temporary" violations.**

1. **STAGED ACCEPTANCE (приемка поэтапная).** Every functional step lands on its own branch, is committed and pushed freely, and is presented separately. No silent batching of ten features into one "it compiles".
2. **MAC-VERIFIED, NOT VIBES-VERIFIED (проверка на Маке).** Every functional step is verified on the operator's Mac: built, installed, launched on the real machine. Tests, schemas, and batteries are evidence, not delivery.
3. **DEMONSTRATE AND AGREE (демонстрировать и согласовывать).** Frontend, backend, and design are each shown running to the operator and accepted by him. Done = demonstrated. "Presumed working by synthetic steps" is a draft.
4. **ONE PRODUCT, ONE JURISDICTION, ONE SKIN.** No combined interfaces wearing flags. A feature belongs to its own product, with its own data store and its own primary locale. A cosmetic switch — an env var, a hidden tab, a renamed bundle — is not a product.
5. **NEVER STRAND THE OPERATOR'S DATA.** No silent migrations, no fresh empty databases substituted for real ones, no hidden paths. Any data-touching step is presented to the operator first, with the choice in his hands.
6. **REJECTION IS CLEAN.** What fails the demonstration loses its usable pieces to the library through a salvage audit; the rest is deleted. Applications do not linger as zombie installs.
7. **COMMIT FREELY, HIDE NOTHING.** Over-caution that keeps work invisible is a defect, not a virtue. "Do not commit / do not run / wait for approval" is void for feature branches. The only legitimate waits: merges to canonical main, signing, production credentials, releases.
8. **NO CULTURAL REVOLUTION IN THE REPO.** Researchers and engineers are not beaten with the chair of process; corrections are diffs with evidence, aimed at code, never at persons. Критикуем код, а не людей.

*Precedent of record: the VoxFaktura 1.6.6 chimera, voxfaktura-claw @ 4f3ed3d — one `VITE_VOXFAKTURA_DEFAULT_TAB` variable sold as "two products". Archived on the Kunstkamera shelf. Do not reincarnate it.*
