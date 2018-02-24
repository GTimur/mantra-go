# Мантры Go

Согласованность это не параллельность.
Хотя в Go делается всё, чтобы это скрыть.

Не связывайтесь путём совместного использования памяти,
Но совместно используйте память путём связи.

В параллельных программах всегда следует предпочесть ясность и сопротивляться преждевременной оптимизации.
(Речь об использовании defer mutex.Unlock вместо явного вызова mutex.Unlock)

Чем меньше интерфейс, тем сильнее его представление.

Нулевые значения должны приносить пользу.

“The purpose of abstraction is not to be vague, but to create a new semantic level in which one can be absolutely precise.” - Edsger W. Dijkstra

“A good API is not just easy to use but also hard to misuse.” - JBD

“Making things easy to do is a false economy. Focus on making things easy to understand and the rest will follow.” - Peter Bourgon

“This is a cardinal sin amongst programmers. If code looks like it’s doing one thing when it’s actually doing something else, someone down the road will read that code and misunderstand it, and use it or alter it in a way that causes bugs. That someone might be you, even if it was your code in the first place.” - Nate Finch
