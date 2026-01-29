Для файла cat_tests.py были написаны тесты в test.py, а именно:

6 модульных мокированных тестов
Для функции get_fact():

Тест, проверяющий плохое соединение с сервером - test_get_fact_bad_connection
Тест, проверяющий пустую строку факта - test_get_fact_null
Тест, проверяющий успешное получение факта - test_get_fact_good_response
Для функции get_fact_analysis():

Тест, проверяющий корректность длины при пустой строке факта - test_get_fact_analysis_zero_length
Тест, проверяющий корректность частот символов при пустой строке факта - test_get_fact_analysis_null_frequencies
Тест, проверяющий успешный анализ факта - test_get_fact_analysis_good_response
1 функциональный тест
Тест, проверяющий корректность работы всего процесса - test_correct_functioning