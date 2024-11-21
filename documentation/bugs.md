## <h1 align=center>5+ QA Issues/Bugs<h1>

---

1. **Description:** Nickname committed to the user table using the /register/ API was replaced by an autogenerated one.\
    **Issue Link:** <a href="https://github.com/dylandacosta8/is601_final/issues/12"> here </a>\
    **Resolution:** Replaced the generate_nickname() method with the nickname passed in as a part of the user data.
    <br>

2. **Description:** Swagger UI default endpoint data mismatch.\
    **Issue Link:** <a href="https://github.com/dylandacosta8/is601_final/issues/15"> here </a>\
    **Resolution:** Replaced all instances of generate_nickname() method with static nicknames for all API endpoints.\
    <br>

3. **Description:** No password requirements enforced.\
    **Issue Link:** <a href="https://github.com/dylandacosta8/is601_final/issues/17"> here </a>\
    **Resolution:** Added validation in place for passwords so that they have a minimum length of 6 characters, include at least one capital letter, include at least 1 number and include at least 1 special character.\
    <br>

4. **Description:** No validation to verify if profile_picture_url link includes images in an acceptable image format.\
    **Issue Link:** <a href="https://github.com/dylandacosta8/is601_final/issues/19"> here </a>\
    **Resolution:** Added validation in place for profile_picture_url so that it only accepts links that end in a valid image format such as .jpg, .jpeg and .png\
    <br>

5. **Description:** Verification url generated received User ID as None\
    **Issue Link:** <a href="https://github.com/dylandacosta8/is601_final/issues/9"> here </a>\
    **Resolution:** Added and commited user to the database before sending the email. \
    <br>

6. **Description:** Dockerfile not building due to dependency issue. \
    **Issue Link:** <a href="https://github.com/dylandacosta8/is601_final/issues/1"> here </a>\
    **Resolution:** Bumped libc-bin version in Dockerfile to 2.36-9+deb12u9 \
    <br>