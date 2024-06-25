---
marp: true
---

# Better Public Transport Information in Thailand

by Ruslan Doga and Rail Akhmetov

---

# Executive Summary

Our goal is to improve public transport information in Thailand. We will create a [GTFS](https://gtfs.org) data management platform and a GTFS and [GTFS-RT](https://gtfs.org/realtime/reference/) serving platform.

We plan to work with Thai government agencies and integrate the system with [Google Maps](https://www.google.com/maps/about) through the [Google Transit](https://developers.google.com/transit) program. This will provide accurate and easy-to-access public transport information, making life better for residents and tourists.

---

<!-- class: invert -->
<!-- backgroundColor: #191919-->
<!-- footer: ❤️ BTS -->

# tl;dr

We want to transform Google Maps in Bangkok from [this ...](https://www.google.com/maps/place/Phloen+Chit/@13.7484202,100.5365788,16z/data=!4m8!3m7!1s0x30e29edcfb15ae2b:0xb3f399fbdb9ddf6c!6m1!1v2!8m2!3d13.743044!4d100.548974!16s%2Fm%2F05f879r?entry=ttu)

![bg right:60% contain](https://gist.github.com/assets/67764432/f377b290-df0c-40c6-8535-d6f329d81d01)

---

<!-- footer: ❤️ Tokyo -->

... to something more like [this!](https://www.google.com/maps/place/Shibuya+Station/@35.6580339,139.7016358,17z/data=!3m1!5s0x60188b57f546295f:0x486cece41a7b21b0!4m8!3m7!1s0x60188b563b00109f:0x337328def1e2ab26!6m1!1v2!8m2!3d35.6580339!4d139.7016358!16zL20vMDIya3dq?entry=ttu)

![bg right:60% contain](https://gist.github.com/assets/67764432/0a38d302-3108-43be-8bed-d8a430334f00)

---

<!-- class: default -->
<!-- footer: "" -->
<!-- backgroundColor: default -->

# Company

We plan to start a company with the mission to enhance public transport information in Thailand. Our focus will be on creating simple and effective solutions to improve the accuracy and availability of transport data.

---

# Mission

To provide accurate and accessible public transport information in Thailand through Google Maps integration, making it easier for people to use and rely on public transportation.

---

# Vision

A future where Google Maps provides passengers with accurate, real-time public transport information, including train locations, timetables, fares, and delay updates. This will ensure that the online information matches the real-world excellence of the BTS system!

---

# Team

- Ruslan Doga: Co-Founder - responsible for overall product strategy and development.
- Rail Akhmetov: Co-Founder - responsible for identifying new business opportunities, partnerships, and strategic alliances.

---

# Products

- [GTFS Data Management Platform](#gtfs-data-management-platform)
- [GTFS-RT Data Collection and Serving Platform](#gtfs-rt-data-collection-and-serving-platform)
- [(Optional) Mobile App for Bus Drivers](#optional-mobile-app)

---

# GTFS Data Management Platform

A simple and user-friendly platform tailored for Thai transit agencies to provide accurate public transport information for Google Maps.

1. Government officials use a website to enter and update their transport information.
1. The platform converts this data into a [GTFS Schedule archive.](https://gtfs.org/schedule/reference/)
1. [Google Transit](https://developers.google.com/transit) pulls the GTFS Schedule archive.
1. The schedule information is then displayed on [Google Maps](https://www.google.com/maps/about) as static data, including timetables, ticket fares, and more.

---

# GTFS-RT Data Collection and Serving Platform

A platform integrated with public transport operators to collect and provide real-time location data for Google Maps.

1. Real-time data, such as raw GPS data from BTS trains, is collected.
1. The platform transforms this data into a [GTFS-RT feed.](https://gtfs.org/realtime/reference/)
1. [Google Transit](https://developers.google.com/transit) pulls the GTFS-RT feed.
1. The real-time information is displayed on [Google Maps](https://www.google.com/maps/about) as dynamic data, including current train locations and estimated arrival times.

---

# (Optional) Mobile App

A potential Android app designed to collect real-time location data from buses that do not have built-in GPS.

1. Bus drivers install the Android app on their smartphones.
1. The app is manually activated when the bus is in operation.
1. The app collects real-time GPS data from the smartphone.
1. The app sends the GPS data to [the real-time platform.](#gtfs-rt-data-collection-and-serving-platform)
1. The real-time information is displayed on [Google Maps](https://www.google.com/maps/about) as dynamic data, including current bus locations and estimated arrival times.

---

# Innovation: Accurate Timetables

Our approach provides accurate, up-to-date timetables for Google Maps in Bangkok.

Currently, Google Maps either shows BTS train departures as "every 6 min" (web) or interpolates them (iOS, Android), which is misleading. We ensure precise schedule information, improving user experience.

---

# Innovation: Real-Time Data

Currently, Google Maps does not display real-time train locations, nor does it provide updates on delays or schedule accuracy. Our approach integrates real-time data for buses and trains, filling this gap with accurate, live information. This ensures users have up-to-date details on vehicle locations and any schedule changes.

---

# Other Innovations

- **User-Friendly Tools:** An intuitive website for officials and a mobile app for bus drivers to efficiently collect and manage GTFS data.

- **Seamless Google Maps Integration:** Ensures all data integrates smoothly with Google Maps, enhancing user experience.

---

# Impacted Industry: Public Transport

Our project significantly impacts two key industries:

- - Improved Efficiency: By providing accurate and real-time data, we enhance the efficiency and reliability of public transport systems.
  - User Satisfaction: Passengers benefit from reliable information on schedules, real-time locations, and delays, leading to increased satisfaction and usage of public transport.
  - Operational Insights: Transport authorities can gain valuable insights from data analytics to optimize routes, schedules, and resource allocation.
- Tourism
  - Enhanced Experience: Tourists can easily navigate the public transport system with accurate, real-time information, making their travel experience smoother and more enjoyable.
  - Increased Accessibility: Better public transport information makes tourist attractions more accessible, encouraging more exploration and boosting local businesses.
  - Positive Perception: Reliable transport information improves the overall perception of Thailand as a modern, tourist-friendly destination.

---

# Competition

While there are existing transport information providers, this project's focus on real-time data integration and collaboration with government agencies sets it apart. It would offer a more comprehensive and user-friendly solution.

---

# Trends

Increasing urbanization and the need for sustainable transportation solutions are driving the demand for accurate and accessible transport information. Our platform aligns with these trends, offering timely and relevant solutions.

Also, Japan, Taiwan, and Singapore (countries that implemented GTFS-RT) seem like a good company.

---

# Marketing Strategy

Our target customers are Thai government agencies initially, with plans to expand to other Southeast Asian countries. We will promote our platform through partnerships and demonstrations.

---

# Sales Strategy

We will engage government agencies through direct outreach, showcasing the benefits of our platform. For long-term growth, we will explore commercial opportunities with transport operators and other stakeholders.

---

# Financial Plan

Our platform would be completely self-funded. We have enough experience in this area to know what corners to cut, what needs building, and what is superfluous.

---

# Exit Strategy

Potential exit opportunities include acquisition by a larger transport technology company or public offering.

---

# Funds Required

I work for Pocari Sweat.

---

# Revenue Model

Initially, our project would be non-profit, focusing on public service. In the long term, we will offer our platform as a paid service to other countries and commercial transport operators.

---

# Growth Strategy

- **Phase 1:** Develop core platform, demonstrate real-time demo, and achieve Google Maps integration in a pilot city.
- **Phase 2:** Expand to other Thai cities and collaborate with the Ministry of Transport.
- **Phase 3:** Offer the platform as a paid service to other ASEAN countries.

---

# Why Thailand?

We chose Thailand due to our appreciation for Bangkok's public transport and the opportunity to enhance its digital component.

---

# Thailand’s Benefit

- **Citizen Benefits:** Improved daily travel decisions and increased public transport use.
- **Tourism Boost:** Enhanced tourist experience, easier navigation, and improved Thailand's image as a modern destination.
