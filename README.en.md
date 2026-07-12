# Couple Achievement System

🌐 **Languages / 多語言版本**: [繁體中文](README.md) | [English](README.en.md)

✨ **Online Demo / 線上體驗**: [https://ivanusto.github.io/couple-achievement-list/](https://ivanusto.github.io/couple-achievement-list/)

A relationship tracker and social sharing card generator combining **intimacy milestone check-ins**, a **5x5 interactive relationship map**, and a **romantic journal design style**. Specially designed for couples and spouses to review their relationship, spark excitement, and grow closer.

---

## 🌟 Key Features

1. **Relationship Dashboard**: Live calculation of your couple level (1 level per 10 completed milestones) and custom romantic titles (e.g., `🥚 Newly in Love`, `💖 Sweet Lovers`, `💬 Understanding Partners`, `🔒 Trusting Alliance`, `🔥 Passionate Soulmates`, `🎭 Intimacy Explorers`, `💍 Promised Companions`, up to `♾️ Eternal Love Arch-Mages`).
2. **24 Relationship Domain Nodes**: Interactive grid map where clicking lights up achieved relationship sectors (Daily Romance, Soul Connection, Physical Touch, Adult Adventures, and Lifetime Commitment), updating mastery percentages.
3. **Canvas Radar Chart**: Rendered in vanilla HTML5 Canvas without any third-party library dependencies, charting your progress across all 5 relationship domains.
4. **100 Couple Milestones**: A curated database covering date nights, communications, physical touches, bedroom exploration (including tasteful adult intimacy details), and lifetime milestones.
5. **10 Honor Badges**: Unlock progress-based badges such as `🌱 Dating Rookies`, `💖 Romance Masters`, `💬 Trusting Companions`, `🧠 Ultimate Soulmates`, `✨ Spark Lovers`, and `🔥 Intimacy Wizards` (two-tier system).
6. **One-Click Sharing Card (PNG)**: Automatically compiles a high-resolution 800x1200 image featuring your nickname, avatar, level, radar graph, badge shelf, and proudest milestones.
7. **Romantic Dual Themes**: Switch between atmospheric "Deep Velvet Rose" (Dark Mode) and delicate "Warm Sakura Coral" (Light Mode) notebook styles.
8. **Backup & Restore**: Autosaved progress via LocalStorage with manual JSON export and import options for cross-device syncing.
9. **Zero Server Backend**: Completely static single HTML page, loading instantly, with 100% of data kept local on your device to ensure privacy.
10. **Custom Couple Goals**: Setup and check-off up to 10 custom, personalized goals that automatically integrate into your statistics and sharing card.

---

## 🛠️ Technical Details

- **Core Stacks**: HTML5 / Vanilla CSS / Vanilla JavaScript (ES6)
- **Visuals & Charts**: HTML5 Canvas API (supports high-res Retina displays)
- **Audio synthesis**: Web Audio API (synthesizes musical chord chimes upon unlocks)
- **Animations**: CSS Keyframes + Canvas physical confetti particle system
- **Storage**: LocalStorage API
- **Internationalization**: Integrated multi-language translation engine (i18n)

---

## 📄 License

This project is open source under the MIT License.
Redesigned based on [life-achievement-list](https://github.com/ivanusto/life-achievement-list).
