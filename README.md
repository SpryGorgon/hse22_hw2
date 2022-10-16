# Ссылки на google colab ноутбуки (также они есть в папке src/)

1. Подготовка файлов для аннотации

https://colab.research.google.com/drive/1GXNNMKXcFAioGRChg7q2Gpt7n3L1Ss9J?usp=sharing

2. Использование полученных файлов для создания аннотированного генома бактерии в формате GenBank

https://colab.research.google.com/drive/1K-BXKgqWfWThkWlTkEvvdsi2OjGxtSyh?usp=sharing

3. Бонусная часть задания

https://colab.research.google.com/drive/1iWBq5PRzW1dyX-Fg8YuKvYaXfaolt3xf?usp=sharing

# Статистика

Предсказано генов всего: 3608

Из них, удалось аннотировать с помощью сравнения с бактерией MIL-1: 3329

Из оставшихся генов, с помощью БД SwissProt удалось аннотировать: 53

Генов без аннотации функции осталось: 226

Для бонусного задания, проценты сходства между рибосомальными РНК и участками в полученной сборке отражены в таблице:

```
# BLASTN 2.6.0+
# Query: TOL_0323 5S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 3 hits found
TOL_0323	scaffold1_cov232	100.000	116	0	0	1	116	841988	841873	5.67e-57	215
TOL_0323	scaffold1_cov232	100.000	116	0	0	1	116	2531384	2531499	5.67e-57	215
TOL_0323	scaffold35_cov581	100.000	99	0	0	1	99	99	1	1.60e-47	183
# BLASTN 2.6.0+
# Query: TOL_2453 5S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 3 hits found
TOL_2453	scaffold1_cov232	98.276	116	2	0	1	116	841988	841873	1.23e-53	204
TOL_2453	scaffold1_cov232	98.276	116	2	0	1	116	2531384	2531499	1.23e-53	204
TOL_2453	scaffold35_cov581	98.990	99	1	0	1	99	99	1	7.44e-46	178
# BLASTN 2.6.0+
# Query: TOL_2454 23S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 5 hits found
TOL_2454	scaffold1_cov232	100.000	2887	0	0	1	2887	2528316	2531202	0.0	5332
TOL_2454	scaffold1_cov232	99.965	2887	1	0	1	2887	845056	842170	0.0	5326
TOL_2454	scaffold35_cov581	100.000	1535	0	0	1353	2887	1815	281	0.0	2835
TOL_2454	scaffold41_cov598	100.000	1051	0	0	215	1265	1051	1	0.0	1941
TOL_2454	scaffold48_cov623	100.000	127	0	0	1	127	127	1	1.30e-61	235
# BLASTN 2.6.0+
# Query: TOL_2455 16S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 3 hits found
TOL_2455	scaffold1_cov232	99.935	1539	1	0	1	1539	846845	845307	0.0	2837
TOL_2455	scaffold1_cov232	99.870	1539	2	0	1	1539	2526527	2528065	0.0	2832
TOL_2455	scaffold32_cov590	99.929	1399	1	0	134	1532	1399	1	0.0	2579
# BLASTN 2.6.0+
# Query: TOL_3250 5S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 3 hits found
TOL_3250	scaffold1_cov232	100.000	116	0	0	1	116	841988	841873	5.67e-57	215
TOL_3250	scaffold1_cov232	100.000	116	0	0	1	116	2531384	2531499	5.67e-57	215
TOL_3250	scaffold35_cov581	100.000	99	0	0	1	99	99	1	1.60e-47	183
# BLASTN 2.6.0+
# Query: TOL_3251 23S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 5 hits found
TOL_3251	scaffold1_cov232	100.000	2887	0	0	1	2887	2528316	2531202	0.0	5332
TOL_3251	scaffold1_cov232	99.965	2887	1	0	1	2887	845056	842170	0.0	5326
TOL_3251	scaffold35_cov581	100.000	1535	0	0	1353	2887	1815	281	0.0	2835
TOL_3251	scaffold41_cov598	100.000	1051	0	0	215	1265	1051	1	0.0	1941
TOL_3251	scaffold48_cov623	100.000	127	0	0	1	127	127	1	1.30e-61	235
# BLASTN 2.6.0+
# Query: TOL_3252 16S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 3 hits found
TOL_3252	scaffold1_cov232	99.935	1539	1	0	1	1539	846845	845307	0.0	2837
TOL_3252	scaffold1_cov232	99.870	1539	2	0	1	1539	2526527	2528065	0.0	2832
TOL_3252	scaffold32_cov590	99.929	1399	1	0	134	1532	1399	1	0.0	2579
# BLASTN 2.6.0+
# Query: TOL_3253 5S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 3 hits found
TOL_3253	scaffold1_cov232	100.000	116	0	0	1	116	841988	841873	5.67e-57	215
TOL_3253	scaffold1_cov232	100.000	116	0	0	1	116	2531384	2531499	5.67e-57	215
TOL_3253	scaffold35_cov581	100.000	99	0	0	1	99	99	1	1.60e-47	183
# BLASTN 2.6.0+
# Query: TOL_3254 23S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 5 hits found
TOL_3254	scaffold1_cov232	100.000	2887	0	0	1	2887	2528316	2531202	0.0	5332
TOL_3254	scaffold1_cov232	99.965	2887	1	0	1	2887	845056	842170	0.0	5326
TOL_3254	scaffold35_cov581	100.000	1535	0	0	1353	2887	1815	281	0.0	2835
TOL_3254	scaffold41_cov598	100.000	1051	0	0	215	1265	1051	1	0.0	1941
TOL_3254	scaffold48_cov623	100.000	127	0	0	1	127	127	1	1.30e-61	235
# BLASTN 2.6.0+
# Query: TOL_3255 16S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 3 hits found
TOL_3255	scaffold1_cov232	99.935	1539	1	0	1	1539	846845	845307	0.0	2837
TOL_3255	scaffold1_cov232	99.870	1539	2	0	1	1539	2526527	2528065	0.0	2832
TOL_3255	scaffold32_cov590	99.929	1399	1	0	134	1532	1399	1	0.0	2579
# BLAST processed 12 queries
```
