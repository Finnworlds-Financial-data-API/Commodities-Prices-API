# Commodities-Prices-API
Finnworlds provides <a href="https://finnworlds.com/bond-yields-api/">Commodities Prices API</a> that is a data delivery format that allows you to get instantly real-time and historical commodities prices data. The commodities prices data focuses on the prices of global fundamental commodity categories such as energy, metals, agriculture, livestock and industrial commodities. Users of commodity prices data get a detailed account of the daily, monthly, weekly and yearly percentage changes in the prices of commodities. Regarding historical coverage, commodities that fall under one specific commodity category vary largely. For example, within the energy commodity category, crude oil dates back to 1988 while coals to 2009. In recent years, commodity prices data has become more and more demanded by various users as it is part of the financial investing opportunities. 

Finnworlds has commodities prices data users of different background. Many amateur and professional investors, trading platforms, economists and developers use the Commodities Prices API. Users of financial background use the data on commodity prices for doing extensive research on both commodities and stock prices while developers for building applications, which process the commodity pricing data as an input. Finnworlds Commodities Prices Database is regularly updated on a weekly and quarterly basis. 

If you are interested in the Commodities Prices API provided by Finnworlds, then <a href="https://finnworlds.com/pricing">Sign up for an API key</a> to get started with the data right away. We do not offer customers free trials. However, we can negotiate a pricing for students and researchers. For specific data use cases, tailored subscriptions are made. Do not hesitate to email us at support@finnworlds.con to discuss your commodity prices data needs, or help you find a solution to a problem. 

<h2>API Features</h2>
<ul><li><strong>Category</strong></li>
<li><strong>Commodity Name</strong></li>
<li><strong>Commodity Unit</strong></li>
<li><strong>Commodity Price</strong></li>
<li><strong>Price Change Day</strong></li>
<li><strong>Percentage Day</strong></li>
<li><strong>Percentage Week</strong></li>
<li><strong>Percentage Month</strong></li>
<li><strong>Percentage Year</strong></li>
<li><strong>Quarter4 2022</strong></li>
<li><strong>Quarter1 2023</strong></li>
<li><strong>Quarter2 2023</strong></li>
<li><strong>Quarter3 2023</strong></li>
<li><strong>Quarter4 2023</strong></li>
<li><strong>Date</strong></li></ul>

<h2>How to access the Commodities Prices Data</h2>



<ul><li><strong>JSON rest API</strong></li><li><strong>Excel CSV download</strong></li><li><strong>PDF reports</strong></li><li><strong>Email link</strong></li></ul>


<h2>Documentation</h2>


Our <a href="https://finnworlds.com/documentation">documentation</a> includes input parameters, output objects with explanation of their meaning, we also provide clear examples on the documentation page of various endpoints and their output. We also have SDKs for Javascript, JQuery, VueJS, Angular, JAVA, PHP, NodeJS, Python, Go, Ruby, C#, R, Strest, Rust, Swift and Scala</p>

<h2>Examples</h2>

https://api.finnworlds.com/api/v1/commodities?key=API-key&category=energy


    {
    "status": {
        "code": 200,
        "message": "OK",
        "details": ""
    },
    "result": {
        "output": [
            {
              "category": "energy",
                "commodity_name": "brent",
                "commodity_unit": "usd/bbl",
                "commodity_price": "90.398",
                "price_change_day": "1.222",
                "percentage_day": "-1.33%",
                "percentage_week": "-4.13%",
                "percentage_month": "-0.29%",
                "percentage_year": "6.25%",
                "quarter4_22": "104.512",
                "quarter1_23": "105.802",
                "quarter2_23": "95.713",
                "quarter3_23": "99.325",
                "date": "2022:10:18"
           },
            {
                "category": "energy",
                "commodity_name": "coal",
                "commodity_unit": "usd/t",
                "commodity_price": "392.15",
                "price_change_day": "0.35",
                "percentage_day": "-0.09%",
                "percentage_week": "1.46%",
                "percentage_month": "-10.68%",
                "percentage_year": "63.84%",
                "quarter4_22": "462.47",
                "quarter1_23": "500.994",
                "quarter2_23": "419.46",
                "quarter3_23": "446.338",
                "date": "2022:10:17"
            },
            {
                "category": "energy",
                "commodity_name": "crude oil",
                "commodity_unit": "usd/bbl",
                "commodity_price": "83.585",
                "price_change_day": "1.876",
                "percentage_day": "-2.19%",
                "percentage_week": "-6.45%",
                "percentage_month": "-2.08%",
                "percentage_year": "2.56%",
                "quarter4_22": "98.313",
                "quarter1_23": "98.617",
                "quarter2_23": "90.471",
                "quarter3_23": "93.342",
                "date": "2022:10:18"
            },
            {
                "category": "energy",
                "commodity_name": "ethanol",
                "commodity_unit": "usd/gal",
                "commodity_price": "2.415",
                "price_change_day": "0.0100",
                "percentage_day": "-0.41%",
                "percentage_week": "-0.82%",
                "percentage_month": "-1.83%",
                "percentage_year": "-2.42%",
                "quarter4_22": "2.743",
                "quarter1_23": "2.764",
                "quarter2_23": "2.553",
                "quarter3_23": "2.608",
                "date": "2022:10:17"
            },
            {
                "category": "energy",
                "commodity_name": "gasoline",
                "commodity_unit": "usd/gal",
                "commodity_price": "2.558",
                "price_change_day": "0.0351",
                "percentage_day": "-1.35%",
                "percentage_week": "-2.64%",
                "percentage_month": "5.92%",
                "percentage_year": "3.33%",
                "quarter4_22": "2.956",
                "quarter1_23": "3.102",
                "quarter2_23": "2.696",
                "quarter3_23": "2.815",
                "date": "2022:10:18"
            },
            {
                "category": "energy",
                "commodity_name": "heating oil",
                "commodity_unit": "usd/gal",
                "commodity_price": "4.018",
                "price_change_day": "0.0672",
                "percentage_day": "-1.64%",
                "percentage_week": "2.22%",
                "percentage_month": "23.30%",
                "percentage_year": "57.46%",
                "quarter4_22": "4.558",
                "quarter1_23": "4.7",
                "quarter2_23": "4.228",
                "quarter3_23": "4.33",
                "date": "2022:10:18"
            },
            {
                "category": "energy",
                "commodity_name": "methanol",
                "commodity_unit": "cny/t",
                "commodity_price": "2778",
                "price_change_day": "17.00",
                "percentage_day": "-0.61%",
                "percentage_week": "-1.80%",
                "percentage_month": "1.02%",
                "percentage_year": "-26.06%",
                "quarter4_22": "3045.201",
                "quarter1_23": "3070.945",
                "quarter2_23": "2949.509",
                "quarter3_23": "2968.053",
                "date": "2022:10:18"
            },
            {
                "category": "energy",
                "commodity_name": "naphtha",
                "commodity_unit": "usd/t",
                "commodity_price": "664.82",
                "price_change_day": "4.10",
                "percentage_day": "0.62%",
                "percentage_week": "-1.82%",
                "percentage_month": "5.40%",
                "percentage_year": "-12.66%",
                "quarter4_22": "721.416",
                "quarter1_23": "732.233",
                "quarter2_23": "671.769",
                "quarter3_23": "696.244",
                "date": "2022:10:17"
            },
            {
                "category": "energy",
                "commodity_name": "natural gas",
                "commodity_unit": "usd/mmbtu",
                "commodity_price": "5.7304",
                "price_change_day": "0.2686",
                "percentage_day": "-4.48%",
                "percentage_week": "-13.12%",
                "percentage_month": "-26.57%",
                "percentage_year": "12.63%",
                "quarter4_22": "7.829",
                "quarter1_23": "8.125",
                "quarter2_23": "6.77",
                "quarter3_23": "7.369",
                "date": "2022:10:18"
            },
            {
                "category": "energy",
                "commodity_name": "propane",
                "commodity_unit": "usd/gal",
                "commodity_price": "0.83",
                "price_change_day": "0.00",
                "percentage_day": "-0.14%",
                "percentage_week": "-5.82%",
                "percentage_month": "-19.86%",
                "percentage_year": "-43.75%",
                "quarter4_22": "0.904",
                "quarter1_23": "0.929",
                "quarter2_23": "0.851",
                "quarter3_23": "0.889",
                "date": "2022:10:17"
            },
            {
                "category": "energy",
                "commodity_name": "ttf gas",
                "commodity_unit": "eur/mwh",
                "commodity_price": "113.22",
                "price_change_day": "14.76",
                "percentage_day": "-11.53%",
                "percentage_week": "-27.78%",
                "percentage_month": "-37.88%",
                "percentage_year": "25.90%",
                "quarter4_22": "196.26",
                "quarter1_23": "220.869",
                "quarter2_23": "159.886",
                "quarter3_23": "177.032",
                "date": "2022:10:18"
            },
            {
                "category": "energy",
                "commodity_name": "uk gas",
                "commodity_unit": "gbp/thm",
                "commodity_price": "191",
                "price_change_day": "41.2500",
                "percentage_day": "-17.76%",
                "percentage_week": "-33.26%",
                "percentage_month": "-32.37%",
                "percentage_year": "-15.45%",
                "quarter4_22": "396.232",
                "quarter1_23": "460.053",
                "quarter2_23": "293.985",
                "quarter3_23": "341.386",
                "date": "2022:10:18"
            },
            {
                "category": "energy",
                "commodity_name": "urals oil",
                "commodity_unit": "usd/bbl",
                "commodity_price": "72.57",
                "price_change_day": "1.87",
                "percentage_day": "-2.51%",
                "percentage_week": "-8.73%",
                "percentage_month": "1.06%",
                "percentage_year": "-11.76%",
                "quarter4_22": "86.229",
                "quarter1_23": "91.96",
                "quarter2_23": "80.613",
                "quarter3_23": "83.4",
                "date": "2022:10:17"
            },
            {
                "category": "energy",
                "commodity_name": "uranium",
                "commodity_unit": "usd/lbs",
                "commodity_price": "51",
                "price_change_day": "0.4000",
                "percentage_day": "0.79%",
                "percentage_week": "4.51%",
                "percentage_month": "4.62%",
                "percentage_year": "6.03%",
                "quarter4_22": "54.748",
                "quarter1_23": "55.786",
                "quarter2_23": "52.207",
                "quarter3_23": "52.508",
                "date": "2022:10:17"
            }


   
   
<h2>Customer Support</h2>

<p>Need help, have questions? <a href="mailto:support@finnworlds.com">Get in touch with Support</a>.</p>

<h2>Legal</h2>

<p>Use of the Finnworlds website, services like API and database are subject to the&nbsp;<a href="https://finnworlds.com/legal/terms-and-conditions-on-finnworlds-data/">Finnworlds terms &amp; Conditions</a></p>























