<html>
   <body>


      <h1 id="mydate"><b>
         <script type="text/javascript">
            var today = new Date();
            var dd = String(today.getDate()).padStart(2, '0');
            var mm = String(today.getMonth() + 1).padStart(2, '0'); //January is 0!
            var yyyy = today.getFullYear();
            today = dd + '/' + mm + '/' + yyyy;
            var todaysDate = today;
            
            var alldates =["1/03/2021",
            "2/03/2021",
            "03/03/2021",
            "04/03/2021",
            "05/03/2021",
            "06/03/2021",
            "07/03/2021",
            "08/03/2021",
            "09/03/2021",
            "10/03/2021",
            "11/03/2021",
            "12/03/2021",
            "13/03/2021",
            "14/03/2021",
            "15/03/2021",
            "16/03/2021",
            "17/03/2021",
            "18/03/2021",
            "19/03/2021",
            "20/03/2021",
            "21/03/2021",
            "22/03/2021",
            "23/03/2021",
            "24/03/2021",
            "25/03/2021",
            "26/03/2021",
            "27/03/2021",
            "28/03/2021",
            "29/03/2021",
            "30/03/2021",
            "31/03/2021",
            "01/04/2021",
            "02/04/2021",
            "03/04/2021",
            "04/04/2021",
            "05/04/2021",
            "06/04/2021",
            "07/04/2021",
            "08/04/2021",
            "09/04/2021",
            "10/04/2021",
            "11/04/2021",
            "12/04/2021",
            "13/04/2021",
            "14/04/2021",
            "15/04/2021",
            "16/04/2021",
            "17/04/2021",
            "18/04/2021",
            "19/04/2021",
            "20/04/2021",
            "21/04/2021",
            "22/04/2021",
            "23/04/2021",
            "24/04/2021",
            "25/04/2021",
            "26/04/2021",
            "27/04/2021",
            "28/04/2021",
            "29/04/2021",
            "30/04/2021",
            "01/05/2021",
            "02/05/2021",
            "03/05/2021",
            "04/05/2021",
            "05/05/2021",
            "06/05/2021",
            "07/05/2021",
            "08/05/2021",
            "09/05/2021",
            "10/05/2021",
            "11/05/2021",
            "12/05/2021",
            "13/05/2021",
            "14/05/2021",
            "15/05/2021",
            "16/05/2021",
            "17/05/2021",
            "18/05/2021",
            "19/05/2021",
            "20/05/2021",
            "21/05/2021",
            "22/05/2021",
            "23/05/2021",
            "24/05/2021",
            "25/05/2021",
            "26/05/2021",
            "27/05/2021",
            "28/05/2021",
            "29/05/2021",
            "30/05/2021",
            "31/05/2021",
            "01/06/2021",
            "02/06/2021",
            "03/06/2021",
            "04/06/2021",
            "05/06/2021",
            "06/06/2021",
            "07/06/2021",
            "08/06/2021",
            "09/06/2021",
            "10/06/2021",
            "11/06/2021",
            "12/06/2021",
            "13/06/2021",
            "14/06/2021",
            "15/06/2021",
            "16/06/2021",
            "17/06/2021",
            "18/06/2021",
            "19/06/2021",
            "20/06/2021",
            "21/06/2021",
            "22/06/2021",
            "23/06/2021",
            "24/06/2021",
            "25/06/2021",
            "26/06/2021",
            "27/06/2021",
            "28/06/2021",
            "29/06/2021",
            "30/06/2021",
            "01/07/2021",
            "02/07/2021",
            "03/07/2021",
            "04/07/2021",
            "05/07/2021",
            "06/07/2021",
            "07/07/2021",
            "08/07/2021",
            "09/07/2021",
            "10/07/2021",
            "11/07/2021",
            "12/07/2021",
            "13/07/2021",
            "14/07/2021",
            "15/07/2021",
            "16/07/2021",
            "17/07/2021",
            "18/07/2021",
            "19/07/2021",
            "20/07/2021",
            "21/07/2021",
            "22/07/2021",
            "23/07/2021",
            "24/07/2021",
            "25/07/2021",
            "26/07/2021",
            "27/07/2021",
            "28/07/2021",
            "29/07/2021",
            "30/07/2021",
            "31/07/2021",
            "01/08/2021",
            "02/08/2021",
            "03/08/2021",
            "04/08/2021",
            "05/08/2021",
            "06/08/2021",
            "07/08/2021",
            "08/08/2021"
            ];
            
            
            
            
            
            var prayerTimes = ["Mon	1/03/2021	Fajr	5:31	|	Dhuhur	1:35	|	Asr	5:14	|	Maghrib	8:05	|	Ishaa	9:15",
            "Tues	2/03/2021	Fajr	5:33	|	Dhuhur	1:35	|	Asr	5:13	|	Maghrib	8:04	|	Ishaa	9:13",
            "Wed	3/03/2021	Fajr	5:34	|	Dhuhur	1:35	|	Asr	5:12	|	Maghrib	8:02	|	Ishaa	9:11",
            "Thur	4/03/2021	Fajr	5:35	|	Dhuhur	1:35	|	Asr	5:12	|	Maghrib	8:01	|	Ishaa	9:10",
            "Friday	5/03/2021	Fajr	5:36	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	5:11	|	Maghrib	7:59	|	Ishaa	9:08",
            "Sat	6/03/2021	Fajr	5:38	|	Dhuhur	1:34	|	Asr	5:10	|	Maghrib	7:58	|	Ishaa	9:07",
            "Sun	7/03/2021	Fajr	5:39	|	Dhuhur	1:34	|	Asr	5:09	|	Maghrib	7:57	|	Ishaa	9:05",
            "Mon	8/03/2021	Fajr	5:40	|	Dhuhur	1:34	|	Asr	5:08	|	Maghrib	7:55	|	Ishaa	9:03",
            "Tues	9/03/2021	Fajr	5:41	|	Dhuhur	1:34	|	Asr	5:07	|	Maghrib	7:54	|	Ishaa	9:02",
            "Wed	10/03/2021	Fajr	5:42	|	Dhuhur	1:33	|	Asr	5:07	|	Maghrib	7:52	|	Ishaa	9:00",
            "Thur	11/03/2021	Fajr	5:43	|	Dhuhur	1:33	|	Asr	5:06	|	Maghrib	7:51	|	Ishaa	8:58",
            "Friday	12/03/2021	Fajr	5:45	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	5:05	|	Maghrib	7:49	|	Ishaa	8:57",
            "Sat	13/03/2021	Fajr	5:46	|	Dhuhur	1:33	|	Asr	5:04	|	Maghrib	7:48	|	Ishaa	8:55",
            "Sun	14/03/2021	Fajr	5:47	|	Dhuhur	1:32	|	Asr	5:03	|	Maghrib	7:46	|	Ishaa	8:54",
            "Mon	15/03/2021	Fajr	5:48	|	Dhuhur	1:32	|	Asr	5:02	|	Maghrib	7:44	|	Ishaa	8:52",
            "Tues	16/03/2021	Fajr	5:49	|	Dhuhur	1:32	|	Asr	5:01	|	Maghrib	7:43	|	Ishaa	8:50",
            "Wed	17/03/2021	Fajr	5:50	|	Dhuhur	1:31	|	Asr	5:00	|	Maghrib	7:41	|	Ishaa	8:49",
            "Thur	18/03/2021	Fajr	5:51	|	Dhuhur	1:31	|	Asr	4:59	|	Maghrib	7:40	|	Ishaa	8:47",
            "Friday	19/03/2021	Fajr	5:52	|	Dhuhur	1:31	|	Asr	4:58	|	Maghrib	7:38	|	Ishaa	8:46",
            "Sat	20/03/2021	Fajr	5:53	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	4:57	|	Maghrib	7:37	|	Ishaa	8:44",
            "Sun	21/03/2021	Fajr	5:54	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	4:56	|	Maghrib	7:35	|	Ishaa	8:42",
            "Mon	22/03/2021	Fajr	5:55	|	Dhuhur	1:30	|	Asr	4:55	|	Maghrib	7:34	|	Ishaa	8:41",
            "Tues	23/03/2021	Fajr	5:56	|	Dhuhur	1:30	|	Asr	4:54	|	Maghrib	7:32	|	Ishaa	8:39",
            "Wed	24/03/2021	Fajr	5:57	|	Dhuhur	1:29	|	Asr	4:53	|	Maghrib	7:31	|	Ishaa	8:38",
            "Thur	25/03/2021	Fajr	5:58	|	Dhuhur	1:29	|	Asr	4:52	|	Maghrib	7:29	|	Ishaa	8:36",
            "Friday	26/03/2021	Fajr	5:59	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	4:51	|	Maghrib	7:28	|	Ishaa	8:34",
            "Sat	27/03/2021	Fajr	6:00	|	Dhuhur	1:28	|	Asr	4:50	|	Maghrib	7:26	|	Ishaa	8:33",
            "Sun	28/03/2021	Fajr	6:01	|	Dhuhur	1:28	|	Asr	4:49	|	Maghrib	7:25	|	Ishaa	8:31",
            "Mon	29/03/2021	Fajr	6:02	|	Dhuhur	1:28	|	Asr	4:47	|	Maghrib	7:23	|	Ishaa	8:30",
            "Tues	30/03/2021	Fajr	6:03	|	Dhuhur	1:28	|	Asr	4:46	|	Maghrib	7:21	|	Ishaa	8:28",
            "Wed	31/03/2021	Fajr	6:04	|	Dhuhur	1:27	|	Asr	4:45	|	Maghrib	7:20	|	Ishaa	8:27",
            "Thur	1/04/2021	Fajr	6:05	|	Dhuhur	1:27	|	Asr	4:44	|	Maghrib	7:18	|	Ishaa	8:25",
            "Friday	2/04/2021	Fajr	6:06	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	4:43	|	Maghrib	7:17	|	Ishaa	8:24",
            "Sat	3/04/2021	Fajr	6:07	|	Dhuhur	1:26	|	Asr	4:42	|	Maghrib	7:15	|	Ishaa	8:22",
            "Sun	4/04/2021	Fajr	5:08	|	Dhuhur	12:26	|	Asr	3:41	|	Maghrib	6:14	|	Ishaa	7:21",
            "Mon	5/04/2021	Fajr	5:09	|	Dhuhur	12:26	|	Asr	3:40	|	Maghrib	6:12	|	Ishaa	7:19",
            "Tues	6/04/2021	Fajr	5:10	|	Dhuhur	12:26	|	Asr	3:39	|	Maghrib	6:11	|	Ishaa	7:18",
            "Wed	7/04/2021	Fajr	5:11	|	Dhuhur	12:25	|	Asr	3:38	|	Maghrib	6:09	|	Ishaa	7:16",
            "Thur	8/04/2021	Fajr	5:11	|	Dhuhur	12:25	|	Asr	3:37	|	Maghrib	6:08	|	Ishaa	7:15",
            "Friday	9/04/2021	Fajr	5:12	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	3:35	|	Maghrib	6:07	|	Ishaa	7:14",
            "Sat	10/04/2021	Fajr	5:13	|	Dhuhur	12:24	|	Asr	3:34	|	Maghrib	6:05	|	Ishaa	7:12",
            "Sun	11/04/2021	Fajr	5:14	|	Dhuhur	12:24	|	Asr	3:33	|	Maghrib	6:04	|	Ishaa	7:11",
            "Mon	12/04/2021	Fajr	5:15	|	Dhuhur	12:24	|	Asr	3:32	|	Maghrib	6:02	|	Ishaa	7:10",
            "Tues	13/04/2021	Fajr	5:16	|	Dhuhur	12:24	|	Asr	3:31	|	Maghrib	6:01	|	Ishaa	7:08",
            "Wed	14/04/2021	Fajr	5:17	|	Dhuhur	12:23	|	Asr	3:30	|	Maghrib	5:59	|	Ishaa	7:07",
            "Thur	15/04/2021	Fajr	5:17	|	Dhuhur	12:23	|	Asr	3:29	|	Maghrib	5:58	|	Ishaa	7:05",
            "Friday	16/04/2021	Fajr	5:18	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	3:28	|	Maghrib	5:57	|	Ishaa	7:04",
            "Sat	17/04/2021	Fajr	5:19	|	Dhuhur	12:23	|	Asr	3:27	|	Maghrib	5:55	|	Ishaa	7:03",
            "Sun	18/04/2021	Fajr	5:20	|	Dhuhur	12:22	|	Asr	3:26	|	Maghrib	5:54	|	Ishaa	7:02",
            "Mon	19/04/2021	Fajr	5:21	|	Dhuhur	12:22	|	Asr	3:25	|	Maghrib	5:52	|	Ishaa	7:00",
            "Tues	20/04/2021	Fajr	5:22	|	Dhuhur	12:22	|	Asr	3:24	|	Maghrib	5:51	|	Ishaa	6:59",
            "Wed	21/04/2021	Fajr	5:22	|	Dhuhur	12:22	|	Asr	3:23	|	Maghrib	5:50	|	Ishaa	6:58",
            "Thur	22/04/2021	Fajr	5:23	|	Dhuhur	12:22	|	Asr	3:22	|	Maghrib	5:49	|	Ishaa	6:57",
            "Friday	23/04/2021	Fajr	5:24	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	3:20	|	Maghrib	5:47	|	Ishaa	6:55",
            "Sat	24/04/2021	Fajr	5:25	|	Dhuhur	12:21	|	Asr	3:19	|	Maghrib	5:46	|	Ishaa	6:54",
            "Sun	25/04/2021	Fajr	5:26	|	Dhuhur	12:21	|	Asr	3:18	|	Maghrib	5:45	|	Ishaa	6:53",
            "Mon	26/04/2021	Fajr	5:26	|	Dhuhur	12:21	|	Asr	3:17	|	Maghrib	5:43	|	Ishaa	6:52",
            "Tues	27/04/2021	Fajr	5:27	|	Dhuhur	12:21	|	Asr	3:16	|	Maghrib	5:42	|	Ishaa	6:51",
            "Wed	28/04/2021	Fajr	5:28	|	Dhuhur	12:21	|	Asr	3:16	|	Maghrib	5:41	|	Ishaa	6:50",
            "Thur	29/04/2021	Fajr	5:29	|	Dhuhur	12:20	|	Asr	3:15	|	Maghrib	5:40	|	Ishaa	6:49",
            "Friday	30/04/2021	Fajr	5:30	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	3:14	|	Maghrib	5:39	|	Ishaa	6:48",
            "Sat	1/05/2021	Fajr	5:30	|	Dhuhur	12:20	|	Asr	3:13	|	Maghrib	5:38	|	Ishaa	6:47",
            "Sun	2/05/2021	Fajr	5:31	|	Dhuhur	12:20	|	Asr	3:12	|	Maghrib	5:36	|	Ishaa	6:46",
            "Mon	3/05/2021	Fajr	5:32	|	Dhuhur	12:20	|	Asr	3:11	|	Maghrib	5:35	|	Ishaa	6:45",
            "Tues	4/05/2021	Fajr	5:33	|	Dhuhur	12:20	|	Asr	3:10	|	Maghrib	5:34	|	Ishaa	6:44",
            "Wed	5/05/2021	Fajr	5:33	|	Dhuhur	12:20	|	Asr	3:09	|	Maghrib	5:33	|	Ishaa	6:43",
            "Thur	6/05/2021	Fajr	5:34	|	Dhuhur	12:20	|	Asr	3:08	|	Maghrib	5:32	|	Ishaa	6:42",
            "Friday	7/05/2021	Fajr	5:35	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	3:07	|	Maghrib	5:31	|	Ishaa	6:41",
            "Sat	8/05/2021	Fajr	5:36	|	Dhuhur	12:20	|	Asr	3:07	|	Maghrib	5:30	|	Ishaa	6:40",
            "Sun	9/05/2021	Fajr	5:36	|	Dhuhur	12:20	|	Asr	3:06	|	Maghrib	5:29	|	Ishaa	6:39",
            "Mon	10/05/2021	Fajr	5:37	|	Dhuhur	12:19	|	Asr	3:05	|	Maghrib	5:28	|	Ishaa	6:38",
            "Tues	11/05/2021	Fajr	5:38	|	Dhuhur	12:19	|	Asr	3:04	|	Maghrib	5:27	|	Ishaa	6:38",
            "Wed	12/05/2021	Fajr	5:39	|	Dhuhur	12:19	|	Asr	3:03	|	Maghrib	5:26	|	Ishaa	6:37",
            "Thur	13/05/2021	Fajr	5:39	|	Dhuhur	12:19	|	Asr	3:03	|	Maghrib	5:25	|	Ishaa	6:36",
            "Friday	14/05/2021	Fajr	5:40	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	3:02	|	Maghrib	5:25	|	Ishaa	6:35",
            "Sat	15/05/2021	Fajr	5:41	|	Dhuhur	12:19	|	Asr	3:01	|	Maghrib	5:24	|	Ishaa	6:35",
            "Sun	16/05/2021	Fajr	5:41	|	Dhuhur	12:19	|	Asr	3:01	|	Maghrib	5:23	|	Ishaa	6:34",
            "Mon	17/05/2021	Fajr	5:42	|	Dhuhur	12:19	|	Asr	3:00	|	Maghrib	5:22	|	Ishaa	6:33",
            "Tues	18/05/2021	Fajr	5:43	|	Dhuhur	12:19	|	Asr	2:59	|	Maghrib	5:21	|	Ishaa	6:33",
            "Wed	19/05/2021	Fajr	5:43	|	Dhuhur	12:20	|	Asr	2:59	|	Maghrib	5:21	|	Ishaa	6:32",
            "Thur	20/05/2021	Fajr	5:44	|	Dhuhur	12:20	|	Asr	2:58	|	Maghrib	5:20	|	Ishaa	6:32",
            "Friday	21/05/2021	Fajr	5:45	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	2:58	|	Maghrib	5:19	|	Ishaa	6:31",
            "Sat	22/05/2021	Fajr	5:45	|	Dhuhur	12:20	|	Asr	2:57	|	Maghrib	5:19	|	Ishaa	6:31",
            "Sun	23/05/2021	Fajr	5:46	|	Dhuhur	12:20	|	Asr	2:57	|	Maghrib	5:18	|	Ishaa	6:30",
            "Mon	24/05/2021	Fajr	5:47	|	Dhuhur	12:20	|	Asr	2:56	|	Maghrib	5:17	|	Ishaa	6:30",
            "Tues	25/05/2021	Fajr	5:47	|	Dhuhur	12:20	|	Asr	2:56	|	Maghrib	5:17	|	Ishaa	6:29",
            "Wed	26/05/2021	Fajr	5:48	|	Dhuhur	12:20	|	Asr	2:55	|	Maghrib	5:16	|	Ishaa	6:29",
            "Thur	27/05/2021	Fajr	5:49	|	Dhuhur	12:20	|	Asr	2:55	|	Maghrib	5:16	|	Ishaa	6:28",
            "Friday	28/05/2021	Fajr	5:49	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	2:54	|	Maghrib	5:15	|	Ishaa	6:28",
            "Sat	29/05/2021	Fajr	5:50	|	Dhuhur	12:20	|	Asr	2:54	|	Maghrib	5:15	|	Ishaa	6:28",
            "Sun	30/05/2021	Fajr	5:50	|	Dhuhur	12:21	|	Asr	2:54	|	Maghrib	5:14	|	Ishaa	6:27",
            "Mon	31/05/2021	Fajr	5:51	|	Dhuhur	12:21	|	Asr	2:53	|	Maghrib	5:14	|	Ishaa	6:27",
            "Tues	1/06/2021	Fajr	5:51	|	Dhuhur	12:21	|	Asr	2:53	|	Maghrib	5:14	|	Ishaa	6:27",
            "Wed	2/06/2021	Fajr	5:52	|	Dhuhur	12:21	|	Asr	2:53	|	Maghrib	5:13	|	Ishaa	6:27",
            "Thur	3/06/2021	Fajr	5:53	|	Dhuhur	12:21	|	Asr	2:53	|	Maghrib	5:13	|	Ishaa	6:26",
            "Friday	4/06/2021	Fajr	5:53	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	2:53	|	Maghrib	5:13	|	Ishaa	6:26",
            "Sat	5/06/2021	Fajr	5:54	|	Dhuhur	12:22	|	Asr	2:52	|	Maghrib	5:12	|	Ishaa	6:26",
            "Sun	6/06/2021	Fajr	5:54	|	Dhuhur	12:22	|	Asr	2:52	|	Maghrib	5:12	|	Ishaa	6:26",
            "Mon	7/06/2021	Fajr	5:55	|	Dhuhur	12:22	|	Asr	2:52	|	Maghrib	5:12	|	Ishaa	6:26",
            "Tues	8/06/2021	Fajr	5:55	|	Dhuhur	12:22	|	Asr	2:52	|	Maghrib	5:12	|	Ishaa	6:26",
            "Wed	9/06/2021	Fajr	5:56	|	Dhuhur	12:22	|	Asr	2:52	|	Maghrib	5:12	|	Ishaa	6:26",
            "Thur	10/06/2021	Fajr	5:56	|	Dhuhur	12:23	|	Asr	2:52	|	Maghrib	5:12	|	Ishaa	6:26",
            "Friday	11/06/2021	Fajr	5:56	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	2:52	|	Maghrib	5:12	|	Ishaa	6:26",
            "Sat	12/06/2021	Fajr	5:57	|	Dhuhur	12:23	|	Asr	2:52	|	Maghrib	5:12	|	Ishaa	6:26",
            "Sun	13/06/2021	Fajr	5:57	|	Dhuhur	12:23	|	Asr	2:52	|	Maghrib	5:12	|	Ishaa	6:26",
            "Mon	14/06/2021	Fajr	5:58	|	Dhuhur	12:23	|	Asr	2:52	|	Maghrib	5:12	|	Ishaa	6:26",
            "Tues	15/06/2021	Fajr	5:58	|	Dhuhur	12:24	|	Asr	2:52	|	Maghrib	5:12	|	Ishaa	6:26",
            "Wed	16/06/2021	Fajr	5:58	|	Dhuhur	12:24	|	Asr	2:52	|	Maghrib	5:12	|	Ishaa	6:26",
            "Thur	17/06/2021	Fajr	5:58	|	Dhuhur	12:24	|	Asr	2:52	|	Maghrib	5:12	|	Ishaa	6:26",
            "Friday	18/06/2021	Fajr	5:59	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	2:52	|	Maghrib	5:12	|	Ishaa	6:26",
            "Sat	19/06/2021	Fajr	5:59	|	Dhuhur	12:24	|	Asr	2:52	|	Maghrib	5:12	|	Ishaa	6:26",
            "Sun	20/06/2021	Fajr	5:59	|	Dhuhur	12:25	|	Asr	2:53	|	Maghrib	5:12	|	Ishaa	6:26",
            "Mon	21/06/2021	Fajr	6:00	|	Dhuhur	12:25	|	Asr	2:53	|	Maghrib	5:12	|	Ishaa	6:27",
            "Tues	22/06/2021	Fajr	6:00	|	Dhuhur	12:25	|	Asr	2:53	|	Maghrib	5:13	|	Ishaa	6:27",
            "Wed	23/06/2021	Fajr	6:00	|	Dhuhur	12:25	|	Asr	2:53	|	Maghrib	5:13	|	Ishaa	6:27",
            "Thur	24/06/2021	Fajr	6:00	|	Dhuhur	12:25	|	Asr	2:54	|	Maghrib	5:13	|	Ishaa	6:27",
            "Friday	25/06/2021	Fajr	6:00	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	2:54	|	Maghrib	5:14	|	Ishaa	6:28",
            "Sat	26/06/2021	Fajr	6:00	|	Dhuhur	12:26	|	Asr	2:54	|	Maghrib	5:14	|	Ishaa	6:28",
            "Sun	27/06/2021	Fajr	6:00	|	Dhuhur	12:26	|	Asr	2:55	|	Maghrib	5:14	|	Ishaa	6:28",
            "Mon	28/06/2021	Fajr	6:01	|	Dhuhur	12:26	|	Asr	2:55	|	Maghrib	5:15	|	Ishaa	6:29",
            "Tues	29/06/2021	Fajr	6:01	|	Dhuhur	12:27	|	Asr	2:55	|	Maghrib	5:15	|	Ishaa	6:29",
            "Wed	30/06/2021	Fajr	6:01	|	Dhuhur	12:27	|	Asr	2:56	|	Maghrib	5:15	|	Ishaa	6:29",
            "Thur	1/07/2021	Fajr	6:01	|	Dhuhur	12:27	|	Asr	2:56	|	Maghrib	5:16	|	Ishaa	6:30",
            "Friday	2/07/2021	Fajr	6:01	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	2:57	|	Maghrib	5:16	|	Ishaa	6:30",
            "Sat	3/07/2021	Fajr	6:01	|	Dhuhur	12:27	|	Asr	2:57	|	Maghrib	5:17	|	Ishaa	6:31",
            "Sun	4/07/2021	Fajr	6:01	|	Dhuhur	12:27	|	Asr	2:57	|	Maghrib	5:17	|	Ishaa	6:31",
            "Mon	5/07/2021	Fajr	6:00	|	Dhuhur	12:28	|	Asr	2:58	|	Maghrib	5:18	|	Ishaa	6:32",
            "Tues	6/07/2021	Fajr	6:00	|	Dhuhur	12:28	|	Asr	2:58	|	Maghrib	5:18	|	Ishaa	6:32",
            "Wed	7/07/2021	Fajr	6:00	|	Dhuhur	12:28	|	Asr	2:59	|	Maghrib	5:19	|	Ishaa	6:33",
            "Thur	8/07/2021	Fajr	6:00	|	Dhuhur	12:28	|	Asr	2:59	|	Maghrib	5:20	|	Ishaa	6:33",
            "Friday	9/07/2021	Fajr	6:00	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	3:00	|	Maghrib	5:20	|	Ishaa	6:34",
            "Sat	10/07/2021	Fajr	6:00	|	Dhuhur	12:28	|	Asr	3:01	|	Maghrib	5:21	|	Ishaa	6:34",
            "Sun	11/07/2021	Fajr	5:59	|	Dhuhur	12:29	|	Asr	3:01	|	Maghrib	5:21	|	Ishaa	6:35",
            "Mon	12/07/2021	Fajr	5:59	|	Dhuhur	12:29	|	Asr	3:02	|	Maghrib	5:22	|	Ishaa	6:35",
            "Tues	13/07/2021	Fajr	5:59	|	Dhuhur	12:29	|	Asr	3:02	|	Maghrib	5:23	|	Ishaa	6:36",
            "Wed	14/07/2021	Fajr	5:59	|	Dhuhur	12:29	|	Asr	3:03	|	Maghrib	5:23	|	Ishaa	6:36",
            "Thur	15/07/2021	Fajr	5:58	|	Dhuhur	12:29	|	Asr	3:03	|	Maghrib	5:24	|	Ishaa	6:37",
            "Friday	16/07/2021	Fajr	5:58	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	3:04	|	Maghrib	5:25	|	Ishaa	6:37",
            "Sat	17/07/2021	Fajr	5:57	|	Dhuhur	12:29	|	Asr	3:05	|	Maghrib	5:26	|	Ishaa	6:38",
            "Sun	18/07/2021	Fajr	5:57	|	Dhuhur	12:29	|	Asr	3:05	|	Maghrib	5:26	|	Ishaa	6:39",
            "Mon	19/07/2021	Fajr	5:57	|	Dhuhur	12:29	|	Asr	3:06	|	Maghrib	5:27	|	Ishaa	6:39",
            "Tues	20/07/2021	Fajr	5:56	|	Dhuhur	12:29	|	Asr	3:07	|	Maghrib	5:28	|	Ishaa	6:40",
            "Wed	21/07/2021	Fajr	5:56	|	Dhuhur	12:29	|	Asr	3:07	|	Maghrib	5:29	|	Ishaa	6:41",
            "Thur	22/07/2021	Fajr	5:55	|	Dhuhur	12:30	|	Asr	3:08	|	Maghrib	5:29	|	Ishaa	6:41",
            "Friday	23/07/2021	Fajr	5:54	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	3:08	|	Maghrib	5:30	|	Ishaa	6:42",
            "Sat	24/07/2021	Fajr	5:54	|	Dhuhur	12:30	|	Asr	3:09	|	Maghrib	5:31	|	Ishaa	6:42",
            "Sun	25/07/2021	Fajr	5:53	|	Dhuhur	12:30	|	Asr	3:10	|	Maghrib	5:32	|	Ishaa	6:43",
            "Mon	26/07/2021	Fajr	5:53	|	Dhuhur	12:30	|	Asr	3:10	|	Maghrib	5:32	|	Ishaa	6:44",
            "Tues	27/07/2021	Fajr	5:52	|	Dhuhur	12:30	|	Asr	3:11	|	Maghrib	5:33	|	Ishaa	6:44",
            "Wed	28/07/2021	Fajr	5:51	|	Dhuhur	12:30	|	Asr	3:12	|	Maghrib	5:34	|	Ishaa	6:45",
            "Thur	29/07/2021	Fajr	5:51	|	Dhuhur	12:30	|	Asr	3:12	|	Maghrib	5:35	|	Ishaa	6:46",
            "Friday	30/07/2021	Fajr	5:50	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	3:13	|	Maghrib	5:36	|	Ishaa	6:47",
            "Sat	31/07/2021	Fajr	5:49	|	Dhuhur	12:29	|	Asr	3:14	|	Maghrib	5:37	|	Ishaa	6:47",
            "Sun	1/08/2021	Fajr	5:48	|	Dhuhur	12:29	|	Asr	3:14	|	Maghrib	5:37	|	Ishaa	6:48",
            "Mon	2/08/2021	Fajr	5:47	|	Dhuhur	12:29	|	Asr	3:15	|	Maghrib	5:38	|	Ishaa	6:49",
            "Tues	3/08/2021	Fajr	5:47	|	Dhuhur	12:29	|	Asr	3:16	|	Maghrib	5:39	|	Ishaa	6:49",
            "Wed	4/08/2021	Fajr	5:46	|	Dhuhur	12:29	|	Asr	3:16	|	Maghrib	5:40	|	Ishaa	6:50",
            "Thur	5/08/2021	Fajr	5:45	|	Dhuhur	12:29	|	Asr	3:17	|	Maghrib	5:41	|	Ishaa	6:51",
            "Friday	6/08/2021	Fajr	5:44	|	Juma 3 sessions: 12:30 (Eng) 13:30 (Arabic) 14:30 (Eng)	|	Asr	3:18	|	Maghrib	5:42	|	Ishaa	6:51",
            "Sat	7/08/2021	Fajr	5:43	|	Dhuhur	12:29	|	Asr	3:18	|	Maghrib	5:42	|	Ishaa	6:52",
            "Sun	8/08/2021	Fajr	5:42	|	Dhuhur	12:29	|	Asr	3:19	|	Maghrib	5:43	|	Ishaa	6:53"];
            
            var a = alldates.indexOf(todaysDate);
            document.write(prayerTimes[a]) === document.getElementById("mydate").value;
            document.getElementById("demo").innerHTML = Math.random();
            
         </script>
      </b></h1>
      <br/>
      <h4 id="myAdvice"><i>
         <script>
            var item = ['*Please note Fajr, Duhur and Asr Prayers have fixed time when prayed at the Masjid. Please visit the masjid for updated times for these prayers.','Please do not gather outsite or inside of the mosque after prayer if COVID restriction is in place.','Plese try to minimize the load of traffic on Jumaa days / Fridays and help to keep our Mosque remain open. Please see if Car pooling, walking or cycling options are available for you. Parking the car a bit far and take the oppirtunity to walk is a healthy option for the ones who are able to do so. JazakAllah Khayer!','Please join the mosque whatsapp group for latest updates about events and changes.','Seerah Lectures are on Tuesdays after Magrib, In Sha Allah','Some brothers have set up direct debit of $1 everyday to go out to the masjid bank account Ma Sha Allah. The day they pass away, there will be a donation coming out from their account, if Allah wills. What a way to secure a good deed on the last day on the face of Earth! May Allah give us ability and accept all of our good deeds.','Ramadan is coming soon, take preprations, if possible apply for leave from work for last 10 days to get most out of the blessed nights by doing more and more Ibadaa In Sha Allah','আসসালামুয়ালাইকুম ওয়া রাহমাতুল্লাহি ওবারাকাতুহু','ٱلسَّلَامُ عَلَيْكُمْ','सलाम अलैकुम','سلام علیکم','Selamün aleyküm'].find((_, i, ar) => Math.random() < 1 / (ar.length - i));document.write(item) === document.getElementById("myAdvice").value;
         </script>    
</i>      </h4>

<h4 id="timer">
         <script type="text/javascript">
            function checklength(i) {
                'use strict';
                if (i < 10) {
                    i = "0" + i;
                }
                return i;
            }
            var minutes, seconds, count, counter, timer;
            count = 75; //seconds
            counter = setInterval(timer, 1000);
            function timer() {
                'use strict';
                count = count - 1;
                minutes = checklength(Math.floor(count / 60));
                seconds = checklength(count - minutes * 60);
                if (count < 0) {
                    clearInterval(counter);
                    return;
                }
                document.getElementById("timer").innerHTML = 'Next Translation of Quranic Verse or Hadith coming In sha Allah in ' + minutes + ':' + seconds + ' ';
                if (count === 0) {
                    location.reload();
                }
            }
         </script>
         <!-- <span id="timer"> -->
      </h4>
	  
      <p id="myitem">
         <script>
            var item = ['Narrated AbuHurayrah,The Prophet (ﷺ) said (More or less meaning): The further one is from the mosque , the greater will be the reward. Sunan Abi Dawud 556, Sahih (Al-Albani)', 'The Prophet sallallaahu alayhi wa sallam (ﷺ) said (More or less meaning) : “There are seven whom Allah will shade in His Shade on the Day when there is no shade except His Shade: a just ruler; a youth who grew up in the worship of Allah, the Mighty and Majestic; a man whose heart is attached to the mosques; two men who love each other for Allah s sake, meeting for that and parting upon that; a man who is called by a woman of beauty and position [for illegal intercourse], but be says: I fear Allah; a man who gives in charity and hides it, such that his left hand does not know what his right hand gives in charity; and a man who remembered Allah in private and so his eyes shed tears.(Bukhari and Muslim)','The Prophet (ﷺ) said (More or less meaning), "If the wife of anyone of you asks permission to go to the mosque, he should not forbid her. Sahih al-Bukhari 5238"','The Prophet (ﷺ) said (More or less meaning): The Last Hour will not come until people vie (i.e. compete) with one another about mosques.Sahih (Al-Albani),Sunan Abi Dawud 449','It was narrated that Abu Hurairah said: The Messenger of Allah said (More or less meaning): When one of you performs ablution and does it well, then he comes to the mosque with no other motive but prayer and not seeking anything other than the prayer, he does not take one step but Allah raises him in status one degree thereby, and takes away one of his sins, until he enters the mosque. When he enters the mosque he is in a state of prayer so long as he is waiting for the prayer. Grade:Sahih (Darussalam). Sunan Ibn Majah 774','Buraidah Al-Aslami narrated that : the Prophet (ﷺ) said (More or less meaning): "Give glad tiding to those who walk to the Masajid in the dark; of a complete light on the Day of Resurrection." Sahih (Darussalam). Jami` at-Tirmidhi 223','Abu Qatadah narrated that : Allah s Messenger (ﷺ) said (More or less meaning): When one of you comes to the Masjid, then let him perform two Rakah before sitting. Sahih (Darussalam). Jami` at-Tirmidhi 316','It was narrated from Zainab Ath-Thaqafiyyah that: The Prophet (ﷺ) said (More or less meaning): Any one of you (women) who wants to go out to the Masjid should not go near any perfume. Grade: Sahih (Darussalam).Sunan an-Nasai 5262','It was narrated from Amr bin Shuaib, from his father, from his grandfather, that the Prophet (ﷺ) forbade reciting poetry in the Masjid. Grade:Hasan (Darussalam). Reference	 : Sunan an-Nasai 715','It was narrated that Jabir said: A man came making announcement of a lost camel in the Masjid, and the Messenger of Allah (ﷺ) said (More or less meaning): May you never find it!. Grade: Sahih (Darussalam).Reference:Sunan an-Nasai 717','It was narrated from Abbad bin Tamim, from his paternal uncle, that he saw the messenger of Allah (ﷺ) lying on his back in the Masjid, placing one leg on top of the other. Grade:  Sahih (Darussalam). Reference: Sunan an-Nasai 721','It was narrated from Ibn Umar, that when he was young and single, with no family, at the time of the Messenger of Allah (ﷺ), he used to sleep in the Masjid of the Prophet (ﷺ).Grade: Sahih (Darussalam). Reference: Sunan an-Nasai 722','Sahl As-Saidi, may Allah be pleased with him, said : I heard the Messenger of Allah (ﷺ) say (More or less meaning) : Whoever is in the Masjid waiting for the prayer, he is in a state of prayer. Grade: Hasan (Darussalam). Reference: Sunan an-Nasai 734','Abu Bakrah narrated that he entered the Masjid when the when the Prophet (ﷺ) was bowing, so he bowed outside the row. The Prophet (ﷺ) said (More or less meaning) : May Allah increase you in keenness, but do not do this again. Grade: Sahih (Darussalam). Reference: Sunan an-Nasai 871','Narrated Buraydah ibn al-Hasib: The Prophet (ﷺ) said (More or less meaning): Give good tidings to those who walk to the mosques in darkness for having a perfect light on the Day of Judgment. Grade: Sahih (Al-Albani) Reference: Sunan Abi Dawud 561','Narrated Zayd ibn Thabit: The Prophet (ﷺ) said (More or less meaning) : The prayer a man offers in his house is more excellent than his prayer in this mosque of mine except obligatory prayer. Grade: Sahih (Al-Albani). Reference : Sunan Abi Dawud 1044','Abu Hurairah narrated that : Allah s Messenger said (More or less meaning) : When one of you is in the Masjid, and he senses wind between his buttocks then he should not exit until he hears a sound or smells an odor. Grade:Sahih  (Darussalam) Reference: Jami at Tirmidhi 75','Jabir (May Allah be pleased with him) reported: I came to the Prophet (ﷺ) when he was in the mosque, and he said to me (More or less meaning) , Perform two Rakah prayer. [Al-Bukhari and Muslim]. Reference : Riyad as-Salihin 1145','Abu Huraira reported: The Messenger of Allah (ﷺ) said (More or less meaning) : He who eats of this plant (garlic) should not approach our mosque and should not harm us with the odour of garlic. Reference: Sahih Muslim 563','Abu Huraira reported that the Messenger of Allah (ﷺ) said (More or less meaning): The parts of land dearest to Allah are its mosques, and the parts most hateful to Allah are markets. Reference : Sahih Muslim 671','"O you who believe, seek help through patience and prayer. Surely, Allah is with those who are patient." More or less meaning of verse 53, Surah Bakarah','And seek help through patience and prayer. Indeed, it is a burden except for the humble—, More or less meaning of verse 45, Surah Bakarah','"Competition for more gains diverts you from Allah, until you end up in your graves."(More or less meaning of the verse 1 and 2 of Surah 102, At Takathur)','"Then, on that Day, you will definitely be questioned about your worldly pleasures." (More or less meaning of Verse 8 Surah 102, At Takathur)','"And remember when your Lord proclaimed, If you are grateful, I will certainly give you more. But if you are ungrateful, surely My punishment is severe." (More or less meaning of Verse 7 Surah 14, Ibrahim)','"And remember, O  Prophet, when the disbelievers conspired to capture, kill, or exile you. They planned, but Allah also planned. And Allah is the best of planners". (More or less meaning of Verse 30 Surah 8, Al-Anfal)','"And honour your parents. If one or both of them reach old age in your care, never say to them even ugh, nor yell at them. Rather, address them respectfully." (More or less meaning of Verse 23 Surah 17, Al-Isra)','"And We have commanded people to honour their parents. Their mothers bore them through hardship upon hardship, and their weaning takes two years. So be grateful to Me and your parents. To Me is the final return." (More or less meaning of Verse 14 Surah 31, Lukman)','"We have commanded people to honour their parents. Their mothers bore them in hardship and delivered them in hardship. Their period of bearing and weaning is thirty months. In time, when the child reaches their prime at the age of forty, they pray, “My Lord! Inspire me to always be thankful for Your favours which You blessed me and my parents with, and to do good deeds that please You. And instil righteousness in my offspring. I truly repent to You, and I truly submit to Your Will.”  (More or less meaning of Verse 15 Surah 46, Al Ahqaf)','"Had We sent down to you O Prophet a revelation in writing and they were to touch it with their own hands, the disbelievers would still have said, “This is nothing but pure magic!” " (More or less meaning of Verse 7 Surah 6, Al-An Am)','"If Allah touches you with harm, none can undo it except Him. And if He touches you with a blessing, He is Most Capable of everything."(More or less translation of Surah no 6, Ayaat no 17, Al-An Am)','"Those to whom We gave the Scripture recognize him to be a true prophet as they recognize their own children. Those who have ruined themselves will never believe."(More or less translation of Surah no 6, Ayaat no 20 Al-An Am)','"There is no moving creature on earth whose provision is not guaranteed by Allah. And He knows where it lives and where it is laid to rest. All is written in a perfect Record."(More or less translation of Surah no 11, Ayaat no 6, Hud)','"If We give people a taste of Our mercy then take it away from them, they become utterly desperate, ungrateful."(More or less translation of Surah no 11, Ayaat no 9, Hud)','But if We give them a taste of prosperity after being touched with adversity, they say, “My ills are gone,” and become totally prideful and boastful,(More or less translation of Surah no 11, Ayaat no 10, Hud)','Or do they say, “He has fabricated this Quran!”? Say, O Prophet, “Produce ten fabricated surahs like it and seek help from whoever you can—other than Allah—if what you say is true!”(More or less translation of Surah no 11, Ayaat no 13, Hud)','Whoever desires only this worldly life and its luxuries, We will pay them in full for their deeds in this life—nothing will be left out. It is they who will have nothing in the Hereafter except the Fire. Their efforts in this life will be fruitless and their deeds will be useless.(More or less translation of Surah no 11, Ayaat no 15 & 16, Hud)','"Surely those who believe, do good, and humble themselves before their Lord will be the residents of Paradise. They will be there forever."(More or less translation of Surah no 11, Ayaat no 23, Hud)','"So he (i.e. Noah / Prophet Nuh) began to build the Ark, and whenever some of the chiefs of his people passed by, they mocked him. He said, “If you laugh at us, we will soon laugh at you similarly. You will soon come to know who will be visited by a humiliating torment in this life and overwhelmed by an everlasting punishment in the next."(More or less translation of Surah no 11, Ayaat no 38 & 39, Hud)','Noah called out to his Lord, saying, “My Lord! Certainly my son is ˹also˺ of my family, Your promise is surely true, and You are the most just of all judges!”. Allah replied, “O Noah! He is certainly not of your family—he was entirely of unrighteous conduct. So do not ask Me about what you have no knowledge of! I warn you so you do not fall into ignorance.” Noah pleaded, “My Lord, I seek refuge in You from asking You about what I have no knowledge of, and unless You forgive me and have mercy on me, I will be one of the losers.” (More or less translation of Surah no 11, Ayaat no 45,46,47, Hud)','And your Lord says, "Call upon Me; I will respond to you." Indeed, those who disdain My worship will enter Hell [rendered] contemptible. (More or less translation of Surah no 40, Ayaat no 60, Gafir)','"O you who have believed, if there comes to you a disobedient one with information, investigate, lest you harm a people out of ignorance and become, over what you have done, regretful." (More or less translation of Surah no 49, Ayaat no 6, Al-Hujurat)','"The believers are but brothers, so make settlement between your brothers. And fear Allah that you may receive mercy." (More or less translation of Surah no 49, Ayaat no 10, Al-Hujurat)','"O you who have believed, avoid much [negative] assumption. Indeed, some assumption is sin. And do not spy or backbite each other. Would one of you like to eat the flesh of his brother when dead? You would detest it. And fear Allah; indeed, Allah is Accepting of repentance and Merciful." (More or less translation of Surah no 49, Ayaat no 12, Al-Hujurat)','"O mankind, indeed We have created you from male and female and made you peoples and tribes that you may know one another. Indeed, the most noble of you in the sight of Allah is the most righteous of you. Indeed, Allah is Knowing and Acquainted." (More or less translation of Surah no 49, Ayaat no 13, Al-Hujurat)','The bedouins say, "We have believed." Say, "You have not [yet] believed; but say [instead], We have submitted, for faith has not yet entered your hearts. And if you obey Allah and His Messenger, He will not deprive you from your deeds of anything. Indeed, Allah is Forgiving and Merciful." (More or less translation of Surah no 49, Ayaat no 14, Al-Hujurat)','They consider it a favor to you that they have accepted Islam. Say, "Do not consider your Islam a favor to me. Rather, Allah has conferred favor upon you that He has guided you to the faith, if you should be truthful." (More or less translation of Surah no 49, Ayaat no 17, Al-Hujurat)','"Man does not utter any word except that with him is an observer prepared [to record]." (More or less translation of Surah no 50, Ayaat no 18, Qaf )','"And the intoxication of death will bring the truth; that is what you were trying to avoid." (More or less translation of Surah no 50, Ayaat no 19, Qaf )','And Paradise will be brought near to the righteous, not far, [will be said], "This is what you were promised - for every returner [to Allah] (i.e. who repents) and keeper [of His covenant], Who feared the Most Merciful unseen and came with a heart returning [in repentance]. Enter it in peace. This is the Day of Eternity." (More or less translation of Surah no 50, Ayaat no 31-34, Qaf )','"And as for man, when his Lord tries him and [thus] is generous to him and favors him, he says, "My Lord has honored me." But when He tries him and restricts his provision, he says, "My Lord has humiliated me." No! But you do not honor the orphan. And you do not encourage one another to feed the poor. And you consume inheritance, devouring [it] altogether, And you love wealth with immense love." (More or less translation of Surah no 89, Ayaat no 15-20, Al Fajr )','"So remember Me; I will remember you. And be grateful to Me and do not deny Me." (More or less translation of Al-Baqarah, verse 152)','"And hasten to forgiveness from your Lord and a garden as wide as the heavens and earth, prepared for the righteous. Who spend [in the cause of Allah] during ease and hardship and who restrain anger and who pardon the people - and Allah loves the doers of good;" (More or less translation of Al-Imran, verse 133 & 134)'].find((_, i, ar) => Math.random() < 1 / (ar.length - i));document.write(item) === document.getElementById("myitem").value;
         </script>    
      <p>And Allah knows the best.</p>
      </p>
      <!-- <h6>Above hadith will change after a minute In Sha Allah</h6> -->
      <!-- <h6 id="demo"></h6> -->
      <!-- <script> -->
      <!-- document.getElementById("demo").innerHTML = Math.random(); -->
      <!-- window.setTimeout(function () { -->
      <!-- window.location.reload(); -->
      <!-- }, 60000); -->
      <!-- </script> -->
      
      
	  
      <h4>admin@virginmarymosque.org.au</h4>
	  <h4>V3.2</h4>
      <style>
         .tada {
         overflow: hidden;
         }
         .bata {
         animation: marquee 60s linear infinite;
         }
         @keyframes marquee {
         from {transform: translateX(100%); }
         to {transform: translateX(-100%); }
         }
      </style>
      <!-- <div class="tada bata"> -->
      <!-- <p>Hi</p> -->
      <!-- </div> -->
      <!-- <h6>This page is set to Auto refresh every 5 seconds:</h6> -->
      <!-- <h6 id="demo"></h6> -->
      <!-- <script> -->
      <!-- document.getElementById("demo").innerHTML = Math.random(); -->
      <!-- window.setTimeout(function () { -->
      <!-- window.location.reload(); -->
      <!-- }, 10000); -->
      <!-- </script> -->
   </body>
</html>
