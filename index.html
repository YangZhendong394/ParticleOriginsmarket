<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Particle Origins · Evolution Simulator</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            background: #0a0a1a;
            color: #ffffff;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 24px 20px 60px;
        }

        .container {
            max-width: 1000px;
            width: 100%;
        }

        /* Header */
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 16px;
            margin-bottom: 40px;
            padding-bottom: 20px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.06);
        }

        .brand {
            display: flex;
            align-items: center;
            gap: 14px;
        }

        .brand-icon {
            width: 48px;
            height: 48px;
            background: linear-gradient(135deg, #6dd5ed, #2193b0);
            border-radius: 14px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 26px;
            box-shadow: 0 6px 20px rgba(33, 147, 176, 0.3);
        }

        .brand-text h1 {
            font-size: 22px;
            font-weight: 700;
            letter-spacing: 0.5px;
        }

        .brand-text .sub {
            font-size: 13px;
            color: rgba(255, 255, 255, 0.4);
            font-weight: 400;
        }

        .lang-selector select {
            background: rgba(255, 255, 255, 0.06);
            color: rgba(255, 255, 255, 0.85);
            border: 1px solid rgba(255, 255, 255, 0.08);
            border-radius: 30px;
            padding: 8px 36px 8px 16px;
            font-size: 13px;
            font-weight: 500;
            appearance: none;
            -webkit-appearance: none;
            cursor: pointer;
            outline: none;
            transition: border 0.2s;
            font-family: inherit;
            background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='8' viewBox='0 0 12 8'%3E%3Cpath d='M1 1l5 5 5-5' stroke='rgba(255,255,255,0.5)' stroke-width='1.5' fill='none' stroke-linecap='round'/%3E%3C/svg%3E");
            background-repeat: no-repeat;
            background-position: right 14px center;
            background-size: 12px 8px;
        }

        .lang-selector select:hover {
            border-color: rgba(109, 213, 237, 0.4);
        }

        .lang-selector select option {
            background: #1a1a2e;
            color: #fff;
        }

        /* Hero */
        .hero {
            text-align: center;
            padding: 30px 0 20px;
        }

        .hero h2 {
            font-size: 36px;
            font-weight: 700;
            background: linear-gradient(135deg, #6dd5ed, #a8edea);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 10px;
            line-height: 1.2;
        }

        .hero .tagline {
            font-size: 18px;
            color: rgba(255, 255, 255, 0.6);
            font-weight: 400;
            margin-bottom: 16px;
        }

        .hero .description {
            max-width: 700px;
            margin: 0 auto 30px;
            font-size: 16px;
            line-height: 1.7;
            color: rgba(255, 255, 255, 0.7);
        }

        .cta-button {
            display: inline-block;
            background: linear-gradient(135deg, #6dd5ed, #2193b0);
            color: #fff;
            font-size: 18px;
            font-weight: 600;
            padding: 14px 44px;
            border-radius: 40px;
            text-decoration: none;
            box-shadow: 0 8px 30px rgba(33, 147, 176, 0.35);
            transition: transform 0.2s, box-shadow 0.2s;
            border: none;
            cursor: default;
        }

        .cta-button:hover {
            transform: scale(1.02);
            box-shadow: 0 12px 40px rgba(33, 147, 176, 0.5);
        }

        .cta-note {
            margin-top: 12px;
            font-size: 13px;
            color: rgba(255, 255, 255, 0.3);
        }

        /* Features */
        .features {
            margin: 60px 0 50px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 24px;
        }

        .feature-card {
            background: rgba(255, 255, 255, 0.03);
            border-radius: 20px;
            padding: 24px 20px;
            border: 1px solid rgba(255, 255, 255, 0.05);
            transition: background 0.2s;
        }

        .feature-card:hover {
            background: rgba(255, 255, 255, 0.06);
        }

        .feature-icon {
            font-size: 28px;
            margin-bottom: 10px;
        }

        .feature-title {
            font-size: 17px;
            font-weight: 600;
            margin-bottom: 6px;
        }

        .feature-desc {
            font-size: 14px;
            color: rgba(255, 255, 255, 0.55);
            line-height: 1.5;
        }

        /* Screenshots placeholder */
        .screenshots {
            margin: 40px 0 50px;
        }

        .screenshots h3 {
            font-size: 20px;
            font-weight: 600;
            margin-bottom: 20px;
            text-align: center;
            color: rgba(255, 255, 255, 0.8);
        }

        .screenshot-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 16px;
        }

        .screenshot-placeholder {
            aspect-ratio: 9 / 19;
            background: linear-gradient(145deg, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0.01));
            border-radius: 20px;
            border: 1px solid rgba(255, 255, 255, 0.06);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            color: rgba(255, 255, 255, 0.2);
            font-size: 14px;
            text-align: center;
            padding: 12px;
            transition: border-color 0.2s;
        }

        .screenshot-placeholder:hover {
            border-color: rgba(109, 213, 237, 0.3);
        }

        .screenshot-placeholder .mock-icon {
            font-size: 40px;
            margin-bottom: 8px;
            opacity: 0.5;
        }

        /* Footer */
        .footer {
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.05);
            text-align: center;
            font-size: 13px;
            color: rgba(255, 255, 255, 0.25);
        }

        .footer a {
            color: rgba(109, 213, 237, 0.6);
            text-decoration: none;
        }

        .footer a:hover {
            color: #6dd5ed;
        }

        @media (max-width: 600px) {
            .hero h2 {
                font-size: 28px;
            }
            .header {
                flex-direction: column;
                align-items: stretch;
            }
            .lang-selector select {
                width: 100%;
            }
            .features {
                grid-template-columns: 1fr;
            }
            .screenshot-grid {
                grid-template-columns: repeat(3, 1fr);
            }
            .cta-button {
                width: 100%;
                text-align: center;
                padding: 14px 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container" id="app">
        <!-- Header -->
        <header class="header">
            <div class="brand">
                <div class="brand-icon">✦</div>
                <div class="brand-text">
                    <h1 id="appName">Particle Origins</h1>
                    <div class="sub" id="appSub">Evolution Simulator</div>
                </div>
            </div>
            <div class="lang-selector">
                <select id="langSelect" onchange="switchLanguage(this.value)">
                    <option value="en">English</option>
                    <option value="zh">中文</option>
                    <option value="ja">日本語</option>
                    <option value="ko">한국어</option>
                    <option value="es">Español (LA)</option>
                    <option value="pt">Português (BR)</option>
                </select>
            </div>
        </header>

        <!-- Hero -->
        <section class="hero">
            <h2 id="heroTitle">Watch particles evolve in a living ecosystem</h2>
            <p class="tagline" id="heroTagline">Simulation · Strategy · Relaxation</p>
            <p class="description" id="heroDesc">
                Control environmental parameters, observe particle reproduction, mutation, and hybridization.
                Create your own unique ecological world.
            </p>
            <div class="cta-button" id="ctaLabel">Download on the App Store</div>
            <div class="cta-note" id="ctaNote">Available for iPhone and iPad</div>
        </section>

        <!-- Features -->
        <section class="features" id="featuresContainer">
            <!-- Feature items will be filled by JS -->
        </section>

        <!-- Screenshots -->
        <section class="screenshots">
            <h3 id="screenshotTitle">Sneak Peek</h3>
            <div class="screenshot-grid">
                <div class="screenshot-placeholder"><div class="mock-icon">🌿</div><span id="scr1">Ecosystem</span></div>
                <div class="screenshot-placeholder"><div class="mock-icon">🧬</div><span id="scr2">Mutation</span></div>
                <div class="screenshot-placeholder"><div class="mock-icon">🎨</div><span id="scr3">Themes</span></div>
                <div class="screenshot-placeholder"><div class="mock-icon">📊</div><span id="scr4">Controls</span></div>
            </div>
        </section>

        <!-- Footer -->
        <footer class="footer">
            <p id="footerText">© 2026 Particle Origins. All rights reserved.</p>
            <p style="margin-top:6px;">
                <a href="#" id="privacyLink">Privacy Policy</a> · <a href="#" id="supportLink">Support</a>
            </p>
        </footer>
    </div>

    <script>
        // ---------- 多语言数据 ----------
        const translations = {
            en: {
                appName: 'Particle Origins',
                appSub: 'Evolution Simulator',
                heroTitle: 'Watch particles evolve in a living ecosystem',
                heroTagline: 'Simulation · Strategy · Relaxation',
                heroDesc: 'Control environmental parameters, observe particle reproduction, mutation, and hybridization. Create your own unique ecological world.',
                ctaLabel: 'Download on the App Store',
                ctaNote: 'Available for iPhone and iPad',
                features: [
                    { icon: '🌱', title: 'Realistic Ecosystem', desc: 'Particles reproduce, mutate, and hybridize autonomously, forming dynamic populations.' },
                    { icon: '🎛️', title: '6 Adjustable Parameters', desc: 'Fine-tune temperature, food, predators, entropy, and more to shape evolution.' },
                    { icon: '🏆', title: '5 Challenge Levels', desc: 'Progress from beginner to master, each with unique objectives and failure conditions.' },
                    { icon: '✨', title: 'Stunning Visual Effects', desc: 'Glowing particles, motion trails, and 5 color themes for a mesmerizing experience.' },
                    { icon: '📴', title: 'Completely Offline', desc: 'No internet required, no permissions asked. Your data stays on your device.' },
                    { icon: '🎨', title: '5 Color Themes', desc: 'Switch between Macaron, Cyber Neon, Monochrome, Deep Sea, and Warm Orange.' }
                ],
                screenshotTitle: 'Sneak Peek',
                scr1: 'Ecosystem',
                scr2: 'Mutation',
                scr3: 'Themes',
                scr4: 'Controls',
                footerText: '© 2026 Particle Origins. All rights reserved.',
                privacyLink: 'Privacy Policy',
                supportLink: 'Support'
            },
            zh: {
                appName: '微元溯生',
                appSub: '粒子种群演化模拟器',
                heroTitle: '在活生生的生态系统中观察粒子演化',
                heroTagline: '模拟 · 策略 · 放松',
                heroDesc: '调控环境参数，观察粒子的繁殖、变异与杂交。创造属于你的独特生态世界。',
                ctaLabel: '在 App Store 下载',
                ctaNote: '适用于 iPhone 和 iPad',
                features: [
                    { icon: '🌱', title: '真实生态模拟', desc: '粒子自主繁殖、变异、杂交，形成动态种群。' },
                    { icon: '🎛️', title: '6 项可调参数', desc: '精细调节温度、食物、天敌、熵值等，塑造演化方向。' },
                    { icon: '🏆', title: '5 个挑战关卡', desc: '从新手到大师，每关都有独特目标和失败条件。' },
                    { icon: '✨', title: '惊艳视觉效果', desc: '发光粒子、运动尾迹、5 套主题色，带来沉浸体验。' },
                    { icon: '📴', title: '完全离线', desc: '无需网络，不申请任何权限。数据只存在你的设备上。' },
                    { icon: '🎨', title: '5 套色彩主题', desc: '可在马卡龙、赛博霓虹、黑白、深海、暖橙间自由切换。' }
                ],
                screenshotTitle: '预览',
                scr1: '生态',
                scr2: '变异',
                scr3: '主题',
                scr4: '控制',
                footerText: '© 2026 微元溯生。保留所有权利。',
                privacyLink: '隐私政策',
                supportLink: '技术支持'
            },
            ja: {
                appName: '微元溯生',
                appSub: 'パーティクル進化シミュレーター',
                heroTitle: '生きた生態系で粒子の進化を見守ろう',
                heroTagline: 'シミュレーション · 戦略 · リラックス',
                heroDesc: '環境パラメータを調整し、粒子の繁殖・変異・交雑を観察。あなただけの独自の生態世界を創り出しましょう。',
                ctaLabel: 'App Store でダウンロード',
                ctaNote: 'iPhone および iPad 対応',
                features: [
                    { icon: '🌱', title: 'リアルな生態系シミュレーション', desc: '粒子が自律的に繁殖・変異・交雑し、動的な個体群を形成します。' },
                    { icon: '🎛️', title: '6 つの調整可能パラメータ', desc: '温度、餌、天敵、エントロピーなどを微調整して進化を導きます。' },
                    { icon: '🏆', title: '5 つのチャレンジステージ', desc: '初心者からマスターまで、各ステージに独自の目標と失敗条件があります。' },
                    { icon: '✨', title: '見事なビジュアルエフェクト', desc: '発光粒子、モーショントレイル、5 つのカラーテーマで没入感を演出。' },
                    { icon: '📴', title: '完全オフライン', desc: 'インターネット不要、権限不要。データはお使いのデバイス上にのみ保存されます。' },
                    { icon: '🎨', title: '5 つのカラーテーマ', desc: 'マカロン、サイバーネオン、モノクローム、深海、ウォームオレンジから選択可能。' }
                ],
                screenshotTitle: 'プレビュー',
                scr1: '生態系',
                scr2: '変異',
                scr3: 'テーマ',
                scr4: 'コントロール',
                footerText: '© 2026 微元溯生。All rights reserved.',
                privacyLink: 'プライバシーポリシー',
                supportLink: 'サポート'
            },
            ko: {
                appName: '미원소생',
                appSub: '입자 진화 시뮬레이터',
                heroTitle: '살아있는 생태계에서 입자의 진화를 지켜보세요',
                heroTagline: '시뮬레이션 · 전략 · 휴식',
                heroDesc: '환경 매개변수를 조정하고 입자의 번식, 돌연변이, 교잡을 관찰하세요. 나만의 독특한 생태계를 창조하십시오.',
                ctaLabel: 'App Store에서 다운로드',
                ctaNote: 'iPhone 및 iPad 지원',
                features: [
                    { icon: '🌱', title: '실제 생태계 시뮬레이션', desc: '입자가 자율적으로 번식, 돌연변이, 교잡을 하여 역동적인 개체군을 형성합니다.' },
                    { icon: '🎛️', title: '6가지 조정 가능한 매개변수', desc: '온도, 먹이, 천적, 엔트로피 등을 미세 조정하여 진화를 유도하세요.' },
                    { icon: '🏆', title: '5가지 도전 스테이지', desc: '초보자부터 마스터까지, 각 스테이지마다 고유한 목표와 실패 조건이 있습니다.' },
                    { icon: '✨', title: '놀라운 시각 효과', desc: '발광 입자, 모션 트레일, 5가지 색상 테마로 몰입감을 선사합니다.' },
                    { icon: '📴', title: '완전 오프라인', desc: '인터넷 불필요, 권한 불필요. 데이터는 기기 내에만 저장됩니다.' },
                    { icon: '🎨', title: '5가지 색상 테마', desc: '마카롱, 사이버 네온, 흑백, 심해, 따뜻한 오렌지 중 선택 가능합니다.' }
                ],
                screenshotTitle: '미리보기',
                scr1: '생태계',
                scr2: '돌연변이',
                scr3: '테마',
                scr4: '제어',
                footerText: '© 2026 미원소생. All rights reserved.',
                privacyLink: '개인정보처리방침',
                supportLink: '지원'
            },
            es: {
                appName: 'Orígenes de Partículas',
                appSub: 'Simulador de Evolución',
                heroTitle: 'Observa cómo las partículas evolucionan en un ecosistema vivo',
                heroTagline: 'Simulación · Estrategia · Relajación',
                heroDesc: 'Controla parámetros ambientales, observa la reproducción, mutación e hibridación de partículas. Crea tu propio mundo ecológico único.',
                ctaLabel: 'Descargar en App Store',
                ctaNote: 'Disponible para iPhone y iPad',
                features: [
                    { icon: '🌱', title: 'Simulación ecológica realista', desc: 'Las partículas se reproducen, mutan e hibridan autónomamente, formando poblaciones dinámicas.' },
                    { icon: '🎛️', title: '6 parámetros ajustables', desc: 'Ajusta temperatura, comida, depredadores, entropía y más para dar forma a la evolución.' },
                    { icon: '🏆', title: '5 niveles de desafío', desc: 'Progresión de principiante a maestro, cada uno con objetivos únicos y condiciones de fallo.' },
                    { icon: '✨', title: 'Efectos visuales impresionantes', desc: 'Partículas brillantes, estelas de movimiento y 5 temas de color para una experiencia cautivadora.' },
                    { icon: '📴', title: 'Completamente offline', desc: 'Sin necesidad de internet, sin permisos. Tus datos permanecen en tu dispositivo.' },
                    { icon: '🎨', title: '5 temas de color', desc: 'Cambia entre Macaron, Neón Cibernético, Monocromático, Azul Profundo y Naranja Cálido.' }
                ],
                screenshotTitle: 'Vista previa',
                scr1: 'Ecosistema',
                scr2: 'Mutación',
                scr3: 'Temas',
                scr4: 'Controles',
                footerText: '© 2026 Orígenes de Partículas. Todos los derechos reservados.',
                privacyLink: 'Política de Privacidad',
                supportLink: 'Soporte'
            },
            pt: {
                appName: 'Origens das Partículas',
                appSub: 'Simulador de Evolução',
                heroTitle: 'Observe as partículas evoluírem em um ecossistema vivo',
                heroTagline: 'Simulação · Estratégia · Relaxamento',
                heroDesc: 'Controle parâmetros ambientais, observe a reprodução, mutação e hibridização das partículas. Crie seu próprio mundo ecológico único.',
                ctaLabel: 'Baixar na App Store',
                ctaNote: 'Disponível para iPhone e iPad',
                features: [
                    { icon: '🌱', title: 'Simulação ecológica realista', desc: 'As partículas se reproduzem, mutam e hibridam autonomamente, formando populações dinâmicas.' },
                    { icon: '🎛️', title: '6 parâmetros ajustáveis', desc: 'Ajuste temperatura, comida, predadores, entropia e mais para moldar a evolução.' },
                    { icon: '🏆', title: '5 fases de desafio', desc: 'Progrida de iniciante a mestre, cada fase com objetivos únicos e condições de falha.' },
                    { icon: '✨', title: 'Efeitos visuais deslumbrantes', desc: 'Partículas brilhantes, rastros de movimento e 5 temas de cor para uma experiência envolvente.' },
                    { icon: '📴', title: 'Completamente offline', desc: 'Sem necessidade de internet, sem permissões. Seus dados permanecem no seu dispositivo.' },
                    { icon: '🎨', title: '5 temas de cor', desc: 'Alterne entre Macaron, Neon Cibernético, Monocromático, Azul Profundo e Laranja Quente.' }
                ],
                screenshotTitle: 'Prévia',
                scr1: 'Ecossistema',
                scr2: 'Mutação',
                scr3: 'Temas',
                scr4: 'Controles',
                footerText: '© 2026 Origens das Partículas. Todos os direitos reservados.',
                privacyLink: 'Política de Privacidade',
                supportLink: 'Suporte'
            }
        };

        // ---------- 切换函数 ----------
        function switchLanguage(lang) {
            const t = translations[lang];
            if (!t) return;

            // 更新头部
            document.getElementById('appName').textContent = t.appName;
            document.getElementById('appSub').textContent = t.appSub;

            // 更新主区域
            document.getElementById('heroTitle').textContent = t.heroTitle;
            document.getElementById('heroTagline').textContent = t.heroTagline;
            document.getElementById('heroDesc').textContent = t.heroDesc;
            document.getElementById('ctaLabel').textContent = t.ctaLabel;
            document.getElementById('ctaNote').textContent = t.ctaNote;

            // 更新特性
            const featuresContainer = document.getElementById('featuresContainer');
            featuresContainer.innerHTML = '';
            t.features.forEach((f) => {
                const card = document.createElement('div');
                card.className = 'feature-card';
                card.innerHTML = `
                    <div class="feature-icon">${f.icon}</div>
                    <div class="feature-title">${f.title}</div>
                    <div class="feature-desc">${f.desc}</div>
                `;
                featuresContainer.appendChild(card);
            });

            // 更新截图标题
            document.getElementById('screenshotTitle').textContent = t.screenshotTitle;
            document.getElementById('scr1').textContent = t.scr1;
            document.getElementById('scr2').textContent = t.scr2;
            document.getElementById('scr3').textContent = t.scr3;
            document.getElementById('scr4').textContent = t.scr4;

            // 更新页脚
            document.getElementById('footerText').textContent = t.footerText;
            document.getElementById('privacyLink').textContent = t.privacyLink;
            document.getElementById('supportLink').textContent = t.supportLink;

            // 更新下拉框
            document.getElementById('langSelect').value = lang;
            document.documentElement.lang = lang;
        }

        // ---------- 默认加载英文 ----------
        document.addEventListener('DOMContentLoaded', function() {
            switchLanguage('en');
        });
    </script>
</body>
</html>
