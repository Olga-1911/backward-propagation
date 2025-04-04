# Реализация метода обратного распространения ошибки для двухслойной полностью связанной нейронной сети

Метод обратного распространения ошибки — это метод вычисления градиента, который используется при обновлении весов многослойного перцептрона. Впервые метод был описан в 1974 году Александром Галушкиным, а также независимо и одновременно Полом Вербосом. Далее существенно развит в 1986 году Дэвидом Румельхартом, Джеффри Хинтоном и Рональдом Уильямсом и независимо и одновременно Барцевым и Охониным (красноярская группа). Это итеративный градиентный алгоритм, который используется с целью минимизации ошибки работы многослойного перцептрона и получения желаемого выхода.

Основная идея этого метода состоит в распространении сигналов ошибки от выходов сети к её входам, в направлении обратном прямому распространению сигналов в обычном режиме работы. Барцев и Охонин предложили обобщающий метод («принцип двойственности»), применимый к более широкому классу систем, включая системы с запаздыванием, распределённые системы и им подобные./

Для возможности применения метода обратного распространения ошибки передаточная функция нейронов должна быть дифференцируема. Метод является изменением классического метода градиентного спуска.
Источник: https://ru.wikipedia.org/wiki/%D0%9C%D0%B5%D1%82%D0%BE%D0%B4_%D0%BE%D0%B1%D1%80%D0%B0%D1%82%D0%BD%D0%BE%D0%B3%D0%BE_%D1%80%D0%B0%D1%81%D0%BF%D1%80%D0%BE%D1%81%D1%82%D1%80%D0%B0%D0%BD%D0%B5%D0%BD%D0%B8%D1%8F_%D0%BE%D1%88%D0%B8%D0%B1%D0%BA%D0%B8
