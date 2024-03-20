# Competence-Bank
## Математика
```mermaid
graph TD;
classDef areaMathStyle fill:#CCFFFF,stroke:#333,stroke-width:1px
classDef areasMath fill:#66FFFF,stroke:#333,stroke-width:1px
classDef jobsMath fill:#99CCFF,stroke:#333,stroke-width:1px
classDef aspectMathStyle fill:#3BE0EC,stroke:#333,stroke-width:1px
classDef jobsMathStyle fill:#66B2FF,stroke:#333,stroke-width:1px

AreaMath(["`**Математические основы ИИ (MF)**`"]):::areaMathStyle -->apectsMath(["Направления"]):::areasMath
apectsMath -->aspectProbabilityStatistics(["Основы теории вероятностей, <br> математической статистики <br> и теории информации"]):::aspectMathStyle
apectsMath -->aspectBayesStatistics(["Байесовская статистика <br> и моделирование"]):::aspectMathStyle
apectsMath -->aspectNumericMethods(["Численные методы"]):::aspectMathStyle
apectsMath -->aspectMLStatistics(["Статистические основы МО"]):::aspectMathStyle
apectsMath -->aspectAdditionalAIMath(["Дополнительные главы <br> математической теории ИИ"]):::aspectMathStyle

AreaMath -->jobsMath(["Трудовые функции"]):::jobsMath
jobsMath -->MathJobsDataAnalyst(["Data Analyst"]):::jobsMathStyle
jobsMath -->MathJobsDomainMLSpecialist(["Domain ML Specialist"]):::jobsMathStyle
jobsMath -->MathJobsMLResearcher(["ML Researcher"]):::jobsMathStyle

click aspectProbabilityStatistics "https://github.com/VoidSubjucator/Competence-Bank/blob/main/Math/AIMathBasics/aspectProbabilityStatistics.md"
click aspectBayesStatistics "https://github.com/VoidSubjucator/Competence-Bank/blob/main/Math/AIMathBasics/aspectBayesStatistics.md"
click aspectNumericMethods "https://github.com/VoidSubjucator/Competence-Bank/blob/main/Math/AIMathBasics/aspectNumericMethods.md"
click aspectMLStatistics "https://github.com/VoidSubjucator/Competence-Bank/blob/main/Math/AIMathBasics/aspectMLStatistics.md"
click aspectAdditionalAIMath "https://github.com/VoidSubjucator/Competence-Bank/blob/main/Math/AIMathBasics/aspectAdditionalAIMath.md"

click MathJobsDataAnalyst "https://github.com/VoidSubjucator/Competence-Bank/blob/main/Math/AIMathBasics/jobDataAnalyst.md"
click MathJobsDomainMLSpecialist "https://github.com/VoidSubjucator/Competence-Bank/blob/main/Math/AIMathBasics/jobDomainMLSpecialist.md"
click MathJobsMLResearcher "https://github.com/VoidSubjucator/Competence-Bank/blob/main/Math/AIMathBasics/jobMLResearcher.md"
```

```mermaid
graph TD;
classDef areaDataEngineeringStyle fill:#FFFF33,stroke:#333,stroke-width:1px
classDef aspectDataEngineeringStyle fill:#3BE0EC,stroke:#333,stroke-width:1px
classDef jobsDataEngineeringStyle fill:#66B2FF,stroke:#333,stroke-width:1px

AreaMath(["`**Математические основы ИИ (MF)**`"]):::areaMathStyle ---apectsMath(["Направления"]):::areasMath
apectsMath ---MathAspect1(["Основы теории вероятностей, <br> математической статистики <br> и теории информации"]):::aspectMathStyle
apectsMath ---MathAspect2(["Байесовская статистика <br> и моделирование"]):::aspectMathStyle

AreaMath ---jobsMath(["Трудовые функции"]):::jobsMath
jobsMath ---MathJobsDataAnalyst(["Data Analyst"]):::jobsMathStyle
jobsMath ---MathJobsDomainMLSpecialist(["Domain ML Specialist"]):::jobsMathStyle
jobsMath ---MathJobsMLResearcher(["ML Researcher"]):::jobsMathStyle

click MathJobsDataAnalyst "https://github.com/VoidSubjucator/Competence-Bank/blob/main/Math/AIMathBasics/DataAnalyst.md"
click MathJobsDomainMLSpecialist "https://github.com/VoidSubjucator/Competence-Bank/blob/main/Math/AIMathBasics/DomainMLSpecialist.md"
click MathJobsMLResearcher "https://github.com/VoidSubjucator/Competence-Bank/blob/main/Math/AIMathBasics/MLResearcher.md"
```

## Разработка

