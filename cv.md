# Denis Sudnikov

## My photo)

![I am here](I.jpg "Hello")

## Code

```React

import React from "react";
import "./App.css";
import Header from "./Components/Header/Header";
import Navbar from "./Components/Navbar/Navbar";
import Profile from "./Components/Profile/Profile";
import Dialogs from "./Components/Dialogs/Dialogs";
import Settings from "./Components/Settings/Settings";
import News from "./Components/News/News";
import Music from "./Components/Music/Music";

import { BrowserRouter, Routes, Route } from "react-router-dom";

const App = (props) => {
  return (
    <BrowserRouter>
      <div className="app-wrapper">
        <Header />
        <Navbar />
        <div className="app-wrapper-content">
          <Routes>
            <Route path="/dialogs/*" element={<Dialogs dialogsPage = {props.state.dialogsPage} dispatch = {props.dispatch} />} />
            <Route path="/profile" element={<Profile profilePage = {props.state.profilePage} dispatch = {props.dispatch} />} />
            <Route path="/music" element={<Music />} />
            <Route path="/settings" element={<Settings />} />
            <Route path="/news" element={<News />} />
          </Routes>
        </div>
      </div>
    </BrowserRouter>
  );
};

export default App;

```

## About me:

- Date: 22.03.2022
- Country: Belarus
- Education: College
- Work experience: None
- English level: Pre-Intermediate

## Briefly story

In 2018, I entered college as a programmer technician. The main programming language was C#.
The secondary programming language was HTML+CSS+JS. In March of last year (2021),
I graduated but for some reason could not continue my studies or work in my specialty.
In February 2022, I tried to go for an internship at Andersen, but did not qualify for reasons unknown to me.
There is no real work experience and portfolio at the moment.
I really want to become a real programmer and get into the team.

## Contacts

- Discord: DenisOle(@FriendOfEveryone)
- Telegram: @TapokBabki
- Telefons:
  - Poland: +48 732572\*\*\*
  - Belarus: +375 25 93172\*\*
- E-mail: d_sudnikov@mail.ru
