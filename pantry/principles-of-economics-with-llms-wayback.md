# Wayback Image Prompts — Principles of Economics with LLMs

Text-to-image prompts generated from the AI Wayback Machine sections in `chapters/`.
Each prompt is anchored to the historical figure named in the chapter section.

```python
principles_of_economics_with_llms = [
    # chapters/01-welcome-to-economics.md — Joan Robinson
    "Joan Robinson (circa 1950, British economist) - middle-aged woman with short wavy hair, economic diagrams nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/02-choice-in-a-world-of-scarcity.md — Lionel Robbins
    "Lionel Robbins (circa 1932, British economist) - middle-aged man in formal suit, scarcity notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/03-demand-and-supply.md — Alfred Marshall
    "Alfred Marshall (circa 1890, British economist) - older Victorian man with white mustache, supply and demand curves nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/04-labor-and-financial-markets.md — Anna Schwartz
    "Anna Schwartz (circa 1963, American economist) - middle-aged woman with glasses, monetary history notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/05-elasticity.md — Antoine Augustin Cournot
    "Antoine Augustin Cournot (circa 1838, French economist and mathematician) - nineteenth-century French scholar, demand curve notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/06-consumer-choices.md — Gary Becker
    "Gary Becker (circa 1976, American economist) - middle-aged man in suit, human capital notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/07-production-costs-and-industry-structure.md — Edith Penrose
    "Edith Penrose (circa 1959, British-American economist) - middle-aged woman with short hair, firm growth notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/08-perfect-competition.md — Léon Walras
    "Léon Walras (circa 1874, French economist) - middle-aged man with beard, general equilibrium notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/09-monopoly.md — Joseph Schumpeter
    "Joseph Schumpeter (circa 1942, Austrian-American economist) - middle-aged man with swept-back hair, innovation notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/10-monopolistic-competition-and-oligopoly.md — Edward Chamberlin
    "Edward Chamberlin (circa 1933, American economist) - young middle-aged man in suit, monopolistic competition diagrams nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/11-monopoly-and-antitrust-policy.md — Lina Khan
    "Lina Khan (circa 2021, British-American legal scholar) - young woman with dark hair, antitrust papers nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/12-environmental-protection-and-negative-externalities.md — Arthur Pigou
    "Arthur Pigou (circa 1920, British economist) - middle-aged man with mustache, externality tax notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/13-positive-externalities-and-public-goods.md — Elinor Ostrom
    "Elinor Ostrom (circa 1990, American political economist) - middle-aged woman with glasses, commons governance notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/14-labor-markets-and-income.md — Claudia Goldin
    "Claudia Goldin (circa 1990, American economic historian) - middle-aged woman with curly hair, labor market tables nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/15-poverty-and-economic-inequality.md — Amartya Sen
    "Amartya Sen (circa 1981, Indian economist and philosopher) - South Asian man with glasses, capability approach notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/16-information-risk-and-insurance.md — George Akerlof
    "George Akerlof (circa 1970, American economist) - middle-aged man with glasses, lemons market notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/17-financial-markets.md — Harry Markowitz
    "Harry Markowitz (circa 1952, American economist) - young man in suit, portfolio frontier nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/18-public-economy.md — James Buchanan
    "James Buchanan (circa 1962, American economist) - middle-aged man with glasses, public choice notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/19-the-macroeconomic-perspective.md — Simon Kuznets
    "Simon Kuznets (circa 1940, Belarusian-American economist) - middle-aged man with glasses, national income tables nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/20-economic-growth.md — Robert Solow
    "Robert Solow (circa 1956, American economist) - middle-aged man in suit, growth model notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/21-unemployment.md — A. W. Phillips
    "A. W. Phillips (circa 1958, New Zealand economist) - middle-aged man in suit, Phillips curve nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/22-inflation.md — Irving Fisher
    "Irving Fisher (circa 1911, American economist) - middle-aged man with mustache, price index notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/23-the-international-trade-and-capital-flows.md — David Ricardo
    "David Ricardo (circa 1817, British political economist) - Regency-era man in formal coat, comparative advantage notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/24-the-aggregate-demand-aggregate-supply-model.md — Paul Samuelson
    "Paul Samuelson (circa 1948, American economist) - middle-aged man with glasses, macroeconomic diagrams nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/25-the-keynesian-perspective.md — John Maynard Keynes
    "John Maynard Keynes (circa 1936, British economist) - middle-aged man with mustache, Cambridge papers nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/26-the-neoclassical-perspective.md — Milton Friedman
    "Milton Friedman (circa 1962, American economist) - middle-aged man with glasses, monetarist charts nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/27-money-and-banking.md — Walter Bagehot
    "Walter Bagehot (circa 1873, British journalist and economist) - Victorian man with beard, banking ledgers nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/28-monetary-policy-and-bank-regulation.md — Marriner Eccles
    "Marriner Eccles (circa 1935, American central banker) - middle-aged man in suit, Federal Reserve documents nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/29-exchange-rates-and-international-capital-flows.md — Robert Mundell
    "Robert Mundell (circa 1961, Canadian economist) - middle-aged man in suit, exchange-rate diagrams nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/30-government-budgets-and-fiscal-policy.md — Cecilia Rouse
    "Cecilia Rouse (circa 2021, American economist) - middle-aged Black woman in blazer, fiscal policy papers nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/31-the-impacts-of-government-borrowing.md — Carmen Reinhart
    "Carmen Reinhart (circa 2010, Cuban-American economist) - middle-aged woman with dark hair, sovereign debt charts nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/32-macroeconomic-policy-around-the-world.md — Esther Duflo
    "Esther Duflo (circa 2005, French-American economist) - young woman with dark hair, development economics notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/33-international-trade.md — Eli Heckscher
    "Eli Heckscher (circa 1919, Swedish economist) - middle-aged man with mustache, trade theory notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
    # chapters/34-globalization-and-protectionism.md — Dani Rodrik
    "Dani Rodrik (circa 2011, Turkish economist) - middle-aged man with glasses, globalization policy notes nearby, historically plausible editorial portrait, face-centered composition, period-appropriate clothing and workspace, accurate to known public portraits or photographs when available, no text, no watermark",
]
```
