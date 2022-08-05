<template>
  <div class="achievementDiv">
    <h1 class="achievementHeading">My Achievement</h1>
    <div class="row rowAchievement">
      <div class="col col-md-12 col-xl-6">
        <div class="achievement">
          <div class="icon">
            <i class="iconShape fa-solid fa-graduation-cap"></i>
          </div>
          <div class="">
            <p class="year">2009 - 2014</p>
            <p class="academy">
              <span class="degree">Secondary School Certificate(SSC)</span>
              <br />
              Ferdous Alam Feroj High School
            </p>
          </div>
        </div>
        <div class="achievement">
          <div class="icon">
            <i class="iconShape fa-solid fa-graduation-cap"></i>
          </div>
          <div class="">
            <p class="year">2014 - 2016</p>
            <p class="academy">
              <span class="degree">Higher Secondary Certificate(HSC)</span>
              <br />
              Ghatail Cantonment Public School & College
            </p>
          </div>
        </div>
        <div class="achievement">
          <div class="icon">
            <i class="iconShape fa-solid fa-graduation-cap"></i>
          </div>
          <div class="">
            <p class="year">2018 - 2022</p>
            <p class="academy">
              <span class="degree">B.Sc. in CSE </span>
              <br />
              <span class="university"
                >International University of Business Agriculture and
                Technology</span
              >
            </p>
          </div>
        </div>
      </div>
      <div class="col col-md-12 col-xl-6">
        <div class="achievement">
          <div class="icon">
            <i class="iconShape fa-solid fa-graduation-cap"></i>
          </div>
          <div class="">
            <p class="year">2019 - 2020</p>
            <p class="academy">
              <span class="gHash">Participation on Google Hash Code</span>
              <br />
              University Rank - 5th
            </p>
          </div>
        </div>
        <div class="achievement">
          <div class="icon">
            <i class="iconShape fa-solid fa-graduation-cap"></i>
          </div>
          <div class="">
            <p class="year">20019 - 2020</p>
            <p class="academy">
              <span class="degree">Battle of Intellects (IUBAT-IUPC)</span>
              <br />
              Team Rank - 4th
            </p>
          </div>
        </div>
        <div class="achievement">
          <div class="icon">
            <i class="iconShape fa-solid fa-graduation-cap"></i>
          </div>
          <div class="">
            <p class="year">2021 - 2022</p>
            <p class="academy">
              <span class="degree">Problem Setter</span>
              <br />
              Battle of Intellects (IUBAT-IUPC)
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "myAchievment",
};
</script>

<style>
.achievementDiv {
  background-color: #111a28;
  color: white;
  padding-top: 15px;
}
.achievementHeading {
  margin-left: 35px;
  padding-bottom: 15px;
}
.rowAchievement {
  padding-right: 30px;
  padding-left: 35px;
}
.achievement {
  /* width: 50%; */
  background-color: rgb(222, 239, 230);
  color: rgb(12, 11, 11);

  border-radius: 10px;
  padding: 70px 100px 20px 100px;
  /* margin-left: 60px; */
  margin-top: 15px;
  display: flex;
  flex-direction: row;
}
.achievement:hover {
  box-shadow: 0 5px 15px rgba(255, 255, 255, 0.3);
  opacity: 95%;
  transition: opacity 0.3s ease-in-out;
}
.icon {
  font-size: 45px;
  margin-left: -50px;
  margin-top: -45px;
}

.year {
  margin-left: 25px;
  margin-top: -40px;
  font-weight: bold;
}
.academy {
  margin-left: 25px;
  margin-top: -15px;
  font-weight: bold;
  font-size: 18px;
}
.degree {
  font-size: 24px;
  font-weight: 700;
}
.university {
  color: black;
  font-size: 12px;
  font-weight: bold;
}
.gHash {
  font-size: 23px;
}

@media only screen and (max-width: 500px) {
  .achievementHeading {
    text-align: center;
  }
  .achievement {
    padding: 65px 100px 0px 100px;
  }
  .academy {
    margin-left: 25px;
    margin-top: -15px;
    font-weight: bold;
    font-size: 12px;
  }
  .degree {
    font-size: 16px;
    font-weight: 700;
  }
  .university {
    color: black;
    font-size: 10px;
    font-weight: bold;
  }
  .gHash {
    font-size: 16px;
  }
}
</style>
