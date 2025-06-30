# test_management
test disc
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Test DISC - Évaluation de Personnalité</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
            color: white;
            padding: 30px;
            text-align: center;
        }

        .header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            font-weight: 300;
        }

        .header p {
            font-size: 1.1em;
            opacity: 0.9;
        }

        .content {
            padding: 40px;
        }

        .welcome-screen, .question-screen, .results-screen {
            display: none;
        }

        .welcome-screen.active, .question-screen.active, .results-screen.active {
            display: block;
        }

        .instructions {
            background: #f8f9ff;
            padding: 25px;
            border-radius: 15px;
            margin-bottom: 30px;
            border-left: 5px solid #4facfe;
        }

        .instructions h3 {
            color: #333;
            margin-bottom: 15px;
            font-size: 1.3em;
        }

        .scale-legend {
            display: flex;
            justify-content: space-between;
            margin: 20px 0;
            padding: 15px;
            background: #fff;
            border-radius: 10px;
            border: 2px solid #e0e6ed;
        }

        .scale-item {
            text-align: center;
            flex: 1;
        }

        .scale-number {
            width: 30px;
            height: 30px;
            border-radius: 50%;
            background: #4facfe;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 5px;
            font-weight: bold;
        }

        .question-card {
            background: #fff;
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 25px;
            border: 2px solid #e0e6ed;
            transition: all 0.3s ease;
        }

        .question-card:hover {
            border-color: #4facfe;
            box-shadow: 0 5px 15px rgba(79, 172, 254, 0.1);
        }

        .question-title {
            font-size: 1.1em;
            margin-bottom: 20px;
            color: #333;
            font-weight: 500;
        }

        .rating-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 10px;
        }

        .rating-option {
            display: flex;
            flex-direction: column;
            align-items: center;
            cursor: pointer;
            padding: 10px;
            border-radius: 10px;
            transition: all 0.3s ease;
            flex: 1;
        }

        .rating-option:hover {
            background: #f0f7ff;
        }

        .rating-circle {
            width: 40px;
            height: 40px;
            border: 3px solid #ddd;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 8px;
            font-weight: bold;
            transition: all 0.3s ease;
        }

        .rating-option input[type="radio"] {
            display: none;
        }

        .rating-option input[type="radio"]:checked + .rating-circle {
            background: #4facfe;
            border-color: #4facfe;
            color: white;
            transform: scale(1.1);
        }

        .rating-label {
            font-size: 0.8em;
            text-align: center;
            color: #666;
            line-height: 1.2;
        }

        .progress-bar {
            width: 100%;
            height: 8px;
            background: #e0e6ed;
            border-radius: 4px;
            margin: 20px 0;
            overflow: hidden;
        }

        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, #4facfe, #00f2fe);
            transition: width 0.3s ease;
            border-radius: 4px;
        }

        .progress-text {
            text-align: center;
            color: #666;
            margin-top: 10px;
        }

        .btn {
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
            color: white;
            border: none;
            padding: 15px 30px;
            border-radius: 25px;
            font-size: 1.1em;
            cursor: pointer;
            transition: all 0.3s ease;
            font-weight: 500;
        }

        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(79, 172, 254, 0.3);
        }

        .btn:disabled {
            opacity: 0.6;
            cursor: not-allowed;
            transform: none;
        }

        .btn-secondary {
            background: #6c757d;
            margin-right: 15px;
        }

        .navigation {
            display: flex;
            justify-content: space-between;
            margin-top: 30px;
        }

        .results-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin: 30px 0;
        }

        .profile-card {
            background: #fff;
            border-radius: 15px;
            padding: 25px;
            text-align: center;
            border: 3px solid #e0e6ed;
            transition: all 0.3s ease;
        }

        .profile-card.dominant {
            border-color: #ff4757;
            background: linear-gradient(135deg, #ff4757 0%, #ff3742 100%);
            color: white;
        }

        .profile-card.influent {
            border-color: #ffa502;
            background: linear-gradient(135deg, #ffa502 0%, #ff9500 100%);
            color: white;
        }

        .profile-card.stable {
            border-color: #2ed573;
            background: linear-gradient(135deg, #2ed573 0%, #17d063 100%);
            color: white;
        }

        .profile-card.consciencieux {
            border-color: #3742fa;
            background: linear-gradient(135deg, #3742fa 0%, #2f32ff 100%);
            color: white;
        }

        .profile-score {
            font-size: 3em;
            font-weight: bold;
            margin: 15px 0;
        }

        .profile-title {
            font-size: 1.4em;
            margin-bottom: 15px;
            font-weight: 600;
        }

        .profile-description {
            font-size: 0.95em;
            line-height: 1.5;
            opacity: 0.9;
        }

        .main-profile {
            grid-column: 1 / -1;
            transform: scale(1.05);
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .analysis-section {
            background: #f8f9ff;
            padding: 30px;
            border-radius: 15px;
            margin: 30px 0;
        }

        .analysis-section h3 {
            color: #333;
            margin-bottom: 20px;
            font-size: 1.4em;
        }

        .chart-container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
        }

        .bar-chart {
            display: flex;
            align-items: end;
            height: 200px;
            gap: 20px;
            padding: 20px 0;
        }

        .bar {
            flex: 1;
            background: linear-gradient(to top, #4facfe, #00f2fe);
            border-radius: 5px 5px 0 0;
            display: flex;
            flex-direction: column;
            justify-content: end;
            align-items: center;
            color: white;
            font-weight: bold;
            transition: all 0.3s ease;
            min-height: 30px;
        }

        .bar:hover {
            transform: scale(1.05);
        }

        .bar-label {
            color: #333;
            margin-top: 10px;
            font-weight: 600;
        }

        .recommendations {
            background: white;
            padding: 25px;
            border-radius: 10px;
            margin-top: 20px;
        }

        .recommendations h4 {
            color: #333;
            margin-bottom: 15px;
        }

        .recommendations ul {
            padding-left: 20px;
        }

        .recommendations li {
            margin-bottom: 8px;
            line-height: 1.4;
        }

        @media (max-width: 768px) {
            .container {
                margin: 10px;
                border-radius: 15px;
            }
            
            .content {
                padding: 20px;
            }
            
            .rating-container {
                flex-direction: column;
                gap: 15px;
            }
            
            .rating-option {
                flex-direction: row;
                width: 100%;
                justify-content: space-between;
                padding: 15px;
                background: #f8f9ff;
                border-radius: 10px;
            }

            .results-grid {
                grid-template-columns: 1fr;
            }

            .bar-chart {
                height: 150px;
                gap: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Test DISC</h1>
            <p>Découvrez votre profil de personnalité professionnelle</p>
        </div>

        <div class="content">
            <!-- Écran d'accueil -->
            <div class="welcome-screen active">
                <div class="instructions">
                    <h3>Instructions</h3>
                    <p>Vous allez répondre à 20 affirmations en vous positionnant sur une échelle de 1 à 5 :</p>
                    <div class="scale-legend">
                        <div class="scale-item">
                            <div class="scale-number">1</div>
                            <div>Pas du tout d'accord</div>
                        </div>
                        <div class="scale-item">
                            <div class="scale-number">2</div>
                            <div>Peu d'accord</div>
                        </div>
                        <div class="scale-item">
                            <div class="scale-number">3</div>
                            <div>Neutre</div>
                        </div>
                        <div class="scale-item">
                            <div class="scale-number">4</div>
                            <div>Plutôt d'accord</div>
                        </div>
                        <div class="scale-item">
                            <div class="scale-number">5</div>
                            <div>Tout à fait d'accord</div>
                        </div>
                    </div>
                    <p><strong>Important :</strong> Répondez instinctivement en pensant à votre comportement habituel au travail ou dans des situations professionnelles.</p>
                </div>
                <div style="text-align: center;">
                    <button class="btn" onclick="startTest()">Commencer le test</button>
                </div>
            </div>

            <!-- Écran des questions -->
            <div class="question-screen">
                <div class="progress-bar">
                    <div class="progress-fill" id="progressFill"></div>
                </div>
                <div class="progress-text" id="progressText">Question 1 sur 20</div>

                <div id="questionContainer"></div>

                <div class="navigation">
                    <button class="btn btn-secondary" id="prevBtn" onclick="previousQuestion()" disabled>Précédent</button>
                    <button class="btn" id="nextBtn" onclick="nextQuestion()">Suivant</button>
                </div>
            </div>

            <!-- Écran des résultats -->
            <div class="results-screen">
                <h2 style="text-align: center; margin-bottom: 30px; color: #333;">Vos Résultats DISC</h2>
                
                <div class="chart-container">
                    <h3>Graphique de vos scores</h3>
                    <div class="bar-chart" id="barChart"></div>
                </div>

                <div class="results-grid" id="resultsGrid"></div>

                <div class="analysis-section">
                    <h3>Analyse de votre profil</h3>
                    <div id="profileAnalysis"></div>
                    
                    <div class="recommendations">
                        <h4>Recommandations pour votre développement :</h4>
                        <div id="recommendations"></div>
                    </div>
                </div>

                <div style="text-align: center; margin-top: 30px;">
                    <button class="btn" onclick="restartTest()">Refaire le test</button>
                </div>
            </div>
        </div>
    </div>

    <script>
        const questions = [
            // Dominant (D)
            { text: "J'aime prendre des décisions rapidement", category: "D" },
            { text: "Je me concentre sur les résultats et les objectifs à atteindre", category: "D" },
            { text: "J'apprécie les environnements compétitifs", category: "D" },
            { text: "Je suis à l'aise pour gérer des conflits ou défendre mes opinions", category: "D" },
            { text: "Je cherche à prendre des responsabilités et diriger des projets", category: "D" },
            
            // Influent (I)
            { text: "Je suis sociable et j'aime interagir avec les autres", category: "I" },
            { text: "Je trouve de l'énergie dans les discussions et les projets collaboratifs", category: "I" },
            { text: "Je m'exprime facilement et avec enthousiasme en public", category: "I" },
            { text: "Je valorise les relations humaines plus que les résultats stricts", category: "I" },
            { text: "J'aime motiver et inspirer les autres", category: "I" },
            
            // Stable (S)
            { text: "Je préfère les environnements calmes et prévisibles", category: "S" },
            { text: "J'accorde de l'importance à la loyauté et à la coopération", category: "S" },
            { text: "J'aime travailler sur le long terme avec des collègues de confiance", category: "S" },
            { text: "Je reste calme et patient dans les situations stressantes", category: "S" },
            { text: "J'ai tendance à éviter les changements brusques ou les conflits directs", category: "S" },
            
            // Consciencieux (C)
            { text: "J'analyse en détail avant de prendre des décisions importantes", category: "C" },
            { text: "Je suis rigoureux et veille à respecter des normes élevées de qualité", category: "C" },
            { text: "Je préfère un environnement structuré avec des règles et des procédures claires", category: "C" },
            { text: "J'ai peur de faire des erreurs et je vérifie mon travail plusieurs fois", category: "C" },
            { text: "Je suis plus à l'aise avec des données ou des faits qu'avec des idées abstraites", category: "C" }
        ];

        let currentQuestion = 0;
        let answers = {};
        let scores = { D: 0, I: 0, S: 0, C: 0 };

        const profileDescriptions = {
            D: {
                title: "Dominant",
                description: "Orienté résultats, direct, énergique et ambitieux. Vous aimez relever des défis et prendre des décisions rapides.",
                color: "dominant"
            },
            I: {
                title: "Influent",
                description: "Sociable, optimiste et persuasif. Vous excellez dans les relations humaines et l'inspiration des équipes.",
                color: "influent"
            },
            S: {
                title: "Stable",
                description: "Patient, fiable et coopératif. Vous privilégiez la stabilité et les relations harmonieuses.",
                color: "stable"
            },
            C: {
                title: "Consciencieux",
                description: "Analytique, précis et méthodique. Vous accordez une grande importance à la qualité et aux détails.",
                color: "consciencieux"
            }
        };

        function startTest() {
            document.querySelector('.welcome-screen').classList.remove('active');
            document.querySelector('.question-screen').classList.add('active');
            displayQuestion();
        }

        function displayQuestion() {
            const question = questions[currentQuestion];
            const container = document.getElementById('questionContainer');
            
            container.innerHTML = `
                <div class="question-card">
                    <div class="question-title">${question.text}</div>
                    <div class="rating-container">
                        ${[1,2,3,4,5].map(value => `
                            <div class="rating-option">
                                <input type="radio" id="q${currentQuestion}_${value}" name="q${currentQuestion}" value="${value}" ${answers[currentQuestion] == value ? 'checked' : ''}>
                                <label for="q${currentQuestion}_${value}" class="rating-circle">${value}</label>
                                <div class="rating-label">${getRatingLabel(value)}</div>
                            </div>
                        `).join('')}
                    </div>
                </div>
            `;

            // Mise à jour de la barre de progression
            const progress = ((currentQuestion + 1) / questions.length) * 100;
            document.getElementById('progressFill').style.width = progress + '%';
            document.getElementById('progressText').textContent = `Question ${currentQuestion + 1} sur ${questions.length}`;

            // Gestion des boutons
            document.getElementById('prevBtn').disabled = currentQuestion === 0;
            document.getElementById('nextBtn').textContent = currentQuestion === questions.length - 1 ? 'Voir les résultats' : 'Suivant';

            // Ajout des event listeners
            const radios = container.querySelectorAll('input[type="radio"]');
            radios.forEach(radio => {
                radio.addEventListener('change', function() {
                    answers[currentQuestion] = parseInt(this.value);
                });
            });
        }

        function getRatingLabel(value) {
            const labels = {
                1: "Pas du tout d'accord",
                2: "Peu d'accord", 
                3: "Neutre",
                4: "Plutôt d'accord",
                5: "Tout à fait d'accord"
            };
            return labels[value];
        }

        function nextQuestion() {
            if (answers[currentQuestion] === undefined) {
                alert('Veuillez sélectionner une réponse avant de continuer.');
                return;
            }

            if (currentQuestion < questions.length - 1) {
                currentQuestion++;
                displayQuestion();
            } else {
                calculateResults();
            }
        }

        function previousQuestion() {
            if (currentQuestion > 0) {
                currentQuestion--;
                displayQuestion();
            }
        }

        function calculateResults() {
            // Reset scores
            scores = { D: 0, I: 0, S: 0, C: 0 };

            // Calculate scores for each category
            questions.forEach((question, index) => {
                if (answers[index] !== undefined) {
                    scores[question.category] += answers[index];
                }
            });

            displayResults();
        }

        function displayResults() {
            document.querySelector('.question-screen').classList.remove('active');
            document.querySelector('.results-screen').classList.add('active');

            // Trouver le profil dominant
            const maxScore = Math.max(...Object.values(scores));
            const dominantProfile = Object.keys(scores).find(key => scores[key] === maxScore);

            // Créer le graphique en barres
            createBarChart();

            // Afficher les cartes de profil
            const resultsGrid = document.getElementById('resultsGrid');
            const sortedProfiles = Object.entries(scores).sort((a, b) => b[1] - a[1]);
            
            resultsGrid.innerHTML = sortedProfiles.map(([profile, score], index) => {
                const profileInfo = profileDescriptions[profile];
                const isMain = index === 0;
                return `
                    <div class="profile-card ${profileInfo.color} ${isMain ? 'main-profile' : ''}">
                        <div class="profile-title">${profileInfo.title} (${profile})</div>
                        <div class="profile-score">${score}</div>
                        <div class="profile-description">${profileInfo.description}</div>
                        ${isMain ? '<div style="margin-top: 15px; font-weight: bold;">🏆 PROFIL PRINCIPAL</div>' : ''}
                    </div>
                `;
            }).join('');

            // Afficher l'analyse
            displayAnalysis(dominantProfile, sortedProfiles);
        }

        function createBarChart() {
            const barChart = document.getElementById('barChart');
            const maxScore = Math.max(...Object.values(scores));
            
            barChart.innerHTML = Object.entries(scores).map(([profile, score]) => {
                const height = (score / maxScore) * 100;
                const profileInfo = profileDescriptions[profile];
                return `
                    <div class="bar" style="height: ${height}%;">
                        <div style="padding: 10px;">${score}</div>
                        <div class="bar-label">${profileInfo.title}</div>
                    </div>
                `;
            }).join('');
        }

        function displayAnalysis(dominantProfile, sortedProfiles) {
            const analysisDiv = document.getElementById('profileAnalysis');
            const recommendationsDiv = document.getElementById('recommendations');
            
            const mainProfile = profileDescriptions[dominantProfile];
            const secondaryProfile = sortedProfiles.length > 1 ? profileDescriptions[sortedProfiles[1][0]] : null;

            let analysis = `
                <p><strong>Votre profil principal est "${mainProfile.title}"</strong> avec un score de ${scores[dominantProfile]} points.</p>
                <p>${mainProfile.description}</p>
            `;

            if (secondaryProfile && sortedProfiles[1][1] > 15) {
                analysis += `
                    <p><strong>Votre profil secondaire est "${secondaryProfile.title}"</strong> avec ${sortedProfiles[1][1]} points, ce qui indique une personnalité nuancée combinant les caractéristiques des deux profils.</p>
                `;
            }

            // Recommandations basées sur le profil principal
            const recommendations = getRecommendations(dominantProfile);
            
            analysisDiv.innerHTML = analysis;
            recommendationsDiv.innerHTML = `<ul>${recommendations.map(rec => `<li>${rec}</li>`).join('')}</ul>`;
        }

        function getRecommendations(profile) {
            const recommendations = {
                D: [
                    "Travaillez sur votre patience et votre écoute active",
                    "Déléguez davantage et faites confiance à votre équipe",
                    "Prenez le temps d'analyser avant de décider",
                    "Développez votre empathie envers les collègues plus réservés"
                ],
                I: [
                    "Structurez davantage vos idées avant de les présenter",
                    "Accordez plus d'attention aux détails et au suivi",
                    "Développez vos compétences d'écoute active",
                    "Planifiez mieux votre temps et vos priorités"
                ],
                S: [
                    "Osez exprimer vos opinions et prendre position",
                    "Développez votre capacité d'adaptation au changement",
                    "Travaillez votre assertivité dans les conflits",
                    "Prenez plus d'initiatives et de risques calculés"
                ],
                C: [
                    "Acceptez que la perfection n'est pas toujours nécessaire",
                    "Développez vos compétences relationnelles",
                    "Apprenez à communiquer de manière plus directe",
                    "Soyez plus flexible face aux changements"
                ]
            };
            return recommendations[profile] || [];
        }

        function restartTest() {
            currentQuestion = 0;
            answers = {};
            scores = { D: 0, I: 0, S: 0, C: 0 };
            
            document.querySelector('.results-screen').classList.remove('active');
            document.querySelector('.welcome-screen').classList.add('active');
        }

        // Initialize the test
        document.addEventListener('DOMContentLoaded', function() {
            // Test is ready
        });
    </script>
</body>
</html>
