# @wayke-se/components-react-boilerplate

> Minimal React & Typescript example for `@wayke-se/components-react`

## Usage

Create an `.env` file in root.
```
WAYKE_HOST=YOUR_HOST_1,YOUR_HOST_2
WAYKE_SEARCH_URL=https://test-ext-api.wayketech.se/vehicles
WAYKE_SEARCH_X_API_KEY=YOUR_API_KEY
WAYKE_GRAPH_QL_URL=https://gql.wayketech.se/query
WAYKE_ECOM_URL=https://ecom.wayketech.se
GOOGLE_MAPS_API_KEY=YOUR_GOOGLE_MAPS_API_KEY
```

Install & start
```bash
npm install
npm start
```

`WAYKE_HOST` can be used instead of using and exposing the `WAYKE_SEARCH_X_API_KEY`. If, for example, your development host is `test.com.localhost`
Update your local host file and add:
127.0.0.1   test.com.localhost
This will change the origin, while still pointing to localhost.
Start the example and open `test.com.localhost:5000`.

To add more hosts, add all to your local host file and then update `WAYKE_HOST` (comma separated):
```
WAYKE_HOST=a.com.localhost,b.com.localhost
```
`a.com.localhost:5000` and `b.com.localhost:5000` can now be accessed.


### Available Routes (Independent)

#### WaykeComposite
[http://localhost:5000](http://localhost:5000)

#### WaykeSearch With WaykeProvider
[http://localhost:5000/search](http://localhost:5000/search)

#### WaykeSearchItem With WaykeProvider
[http://localhost:5000/search-item/d01f79a3-7552-49c4-9d4d-deb3aa581c31](http://localhost:5000/search-item/d01f79a3-7552-49c4-9d4d-deb3aa581c31)

For more information/options/usage see `@wayke-se/components-react`