:mod:`kasi.SpcdeInfoService`
============================

.. py:module:: kasi.SpcdeInfoService


Module Contents
---------------

Classes
~~~~~~~

.. autoapisummary::

   kasi.SpcdeInfoService.SpcdeInfoService




.. class:: SpcdeInfoService(serviceKey)


   국경일정보, 공휴일정보, 24절기정보, 잡절정보를 조회하는 서비스 입니다.

   .. method:: getHoliDeInfo(self, solYear, solMonth=None, numOfRows=None, pageNo=None)

      월별로 구분(국경일), 요일, 공휴일 여부 등의 정보를 제공한다.


   .. method:: getRestDeInfo(self, solYear, solMonth=None, numOfRows=None, pageNo=None)

      월별로 구분(공휴일), 요일, 공휴일 여부 등의 정보를 제공한다.


   .. method:: get24DivisionsInfo(self, solYear, solMonth=None, numOfRows=None, pageNo=None)

      월별로 구분(24절기), 요일, 공휴일 여부 등의 정보를 제공한다.


   .. method:: getSundryDayInfo(self, solYear, solMonth=None, numOfRows=None, pageNo=None)

      월별로 구분(잡절), 요일, 공휴일 여부 등의 정보를 제공한다.



