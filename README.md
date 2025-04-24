# _EstateEase – Smarter Real Estate at Your Fingertips_

EstateEase is a full-stack real estate platform designed to simplify the process of property discovery and listing. With smart recommendations, real-time chat, and trust-driven features like verified seller badges and map-based insights, EstateEase aims to provide a seamless and intelligent user experience.

<br/>

### Features

- **Smart Property Recommendation System**
- **Map Integration with Nearby Essentials** (Schools, Hospitals, etc.)
- **Price Trend Visualizer** using dynamic charts
- **Verified Seller Badge** with KYC document uploads
- **Save Listings and Schedule Property Visits**
- **Real-Time Chat with Sellers** via Firebase or Socket.io
- **Secure Authentication** for users and admins
- **Admin Dashboard** for analytics and verification

<br/>

### Tech Stack

#### Frontend:
- Next.js
- Tailwind CSS
- Next Router
- Axios
- Chart.js / Recharts
- Google Maps API or Mapbox

#### Backend:
- FastAPI
- Supabase
- Firebase Firestore / Socket.io (for chat)

<br/>

### API Endpoints

#### Properties
- `GET /api/properties` – Fetch all properties
- `GET /api/properties/:id` – Fetch a single property
- `POST /api/properties` – Add property (with KYC)
- `PUT /api/properties/:id` – Update property
- `DELETE /api/properties/:id` – Delete property

#### Recommendations & Trends
- `GET /api/recommendations` – Personalized suggestions
- `GET /api/price-trends/:location` – Price trends for area

#### Users & Auth
- `POST /api/users/register` – Register
- `POST /api/users/login` – Login
- `GET /api/users/me` – Profile info

#### Visits & Inquiries
- `POST /api/inquiries` – Send inquiry or schedule visit
- `GET /api/saved` – Get saved properties

#### Chat (Socket.io / Firebase)
- `POST /api/chat/send` – Send message
- `GET /api/chat/:conversationId` – Get conversation

<br/>

### License

This project is open-source and available under the Apache License.

<br/>

### Want to Contribute?

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change or improve.
