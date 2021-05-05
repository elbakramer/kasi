:mod:`kasi.SrAltudeInfoService`
===============================

.. py:module:: kasi.SrAltudeInfoService


Module Contents
---------------

Classes
~~~~~~~

.. autoapisummary::

   kasi.SrAltudeInfoService.SrAltudeInfoService




.. class:: SrAltudeInfoService(serviceKey)


   지역별 태양고도 정보, 위치별 태양고도 정보를 조회하는 서비스 입니다.

   .. attribute:: locations
      

      

   .. method:: getAreaSrAltudeInfo(self, locdate, location)

      날짜와 지역을 기준으로 월별로 시간별 방위각, 태양고도, 남중고도 등의 정보를 제공한다.


   .. method:: getLCSrAltudeInfo(self, locdate, longitude, latitude, dnYn=None)

      오퍼레이션 설명        날짜와 위치를 기준으로 월별로 시간별 방위각, 태양고도, 남중고도 등의 정보를 제공한다.



