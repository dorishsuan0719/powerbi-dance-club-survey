# Dance Club Recruitment Survey Dashboard

A Power BI dashboard analyzing dance club recruitment survey data.

「熱舞社招新問卷」是資料視覺化課程期末專題。  
透過 Power BI 將社團招新問卷資料轉換成視覺化儀表板，分析填答者的基本輪廓、舞風偏好、練習習慣、招新來源，以及舞蹈經驗與參賽意願之間的關係。

## Dashboard Preview

![Power BI Dashboard](powerbi-dashboard-preview.png)

## Project Overview

本專題以熱舞社招新情境為主題，希望透過資料視覺化方式了解潛在社員的背景與需求，並將分析結果作為社團招新、活動安排與訓練規劃的參考。

本專題共使用 **250 份問卷回覆**進行分析。

主要分析內容包括：

- 性別與年級分布
- 科系分布
- 舞蹈經驗比例
- 舞風偏好
- 幹部參與意願
- 每週可接受的練習天數
- 認識熱舞社的管道
- 練習時數與偏好練習方式
- 舞蹈經驗與參賽意願之間的關係

## Dataset

資料來源為課程專題使用的社團招新問卷資料。

- Number of responses: **250**
- Main table: `survey`
- Data format: Excel
- Data source: AI-generated survey data for the course project

主要欄位包含：

- Gender
- Grade
- Department
- Dance experience
- Competition willingness
- Leadership willingness
- Preferred dance style
- Preferred practice method
- Preferred weekly practice frequency
- Practice hours
- Recruitment channel

## Data Preparation

為了支援儀表板分析，本專題建立多個 KPI 與分析用資料表。

### KPI Measures

- Total survey responses
- Percentage of respondents with dance experience
- Average preferred weekly practice days
- Most popular dance style

### Supporting Tables

- `DaysMap`
- `HoursMap`
- `SankeyFlow`

這些資料表主要用於練習天數、練習時數分組，以及桑基圖的流向分析。

## Key Findings

- Survey responses: **250**
- Respondents with dance experience: **56.4%**
- Average preferred practice frequency: **3 days per week**
- Most popular dance style: **Breaking**

## Dashboard Components

### Basic Profile

#### Gender

使用長條圖呈現填答者性別分布，用來了解招新受眾的基本組成。

#### Grade

使用直條圖觀察不同年級的填答人數，可用來了解招新活動主要觸及哪些年級。

#### Department

使用水平長條圖呈現科系分布，協助觀察哪些科系的學生對熱舞社較有興趣。

### Interests and Preferences

#### Preferred Dance Style

使用 Treemap 呈現不同舞風的偏好程度，讓熱門與次熱門舞風可以快速比較。

#### Leadership Willingness

使用 Donut Chart 顯示願意與不願意擔任幹部的比例，作為幹部招募規劃的參考。

### Recruitment and Practice Analysis

#### Recruitment Channel

使用 Funnel Chart 顯示填答者認識熱舞社的主要管道，例如 IG、學長姐推薦、朋友介紹與社團博覽會等。

#### Preferred Weekly Practice Frequency

使用 Line Chart 呈現大家可接受的一週練習天數，作為安排團練頻率的參考。

#### Practice Hours and Preferred Practice Method

使用 Ribbon Chart 分析不同練習時數與練習方式之間的關係，觀察不同練習習慣的受眾偏好。

#### Dance Experience and Competition Willingness

使用 Sankey Diagram 呈現「是否有舞蹈經驗」與「是否想參加比賽」之間的流向關係，用來觀察舞蹈經驗與參賽意願的分布情形。

## Visualizations

The dashboard includes:

- KPI Cards
- Bar Charts
- Column Charts
- Donut Chart
- Treemap
- Funnel Chart
- Line Chart
- Ribbon Chart
- Sankey Diagram

## Tools

- Microsoft Power BI
- Data Visualization
- Power BI Measures
- Data Transformation
- Dashboard Design

## Project Files

- `dashboard.pbix` - Power BI project file
- `report.pdf` - Project report
- `powerbi-dashboard-preview.png` - Dashboard preview image
- `README.md` - Project documentation

## Project Purpose

本作品不只是呈現問卷結果，而是希望透過儀表板將資料轉換成可閱讀的資訊，協助理解社員輪廓、招新來源與練習偏好。

分析結果可作為以下規劃的參考：

- 招新宣傳管道選擇
- 舞風課程安排
- 團練頻率規劃
- 幹部招募
- 比賽培訓規劃

## Course Project

Data Visualization Course Final Project

Developed by YuHsuan Chen.
