  # SISE2601 Project data description - Team name : 10

  This Markdown file describes the data folder structure and organization: 

- **`ResponseId`** *(character)*: A unique character list for each survey participant

- **`add`** *(character)*: Additional things the survey participant wanted to say
  or suggest things for improvement

- **`Progress`** *(numeric)*: The proportion of the survey that was answered in percentage

- **`lang`** *(numeric)*: A variable that tells you in which language the survey
  was answered. (Each number represents a different language)
  We did not receive an analysis of which number is
  appropriate for each language.

  Date columns (the date the specific survey form was completed)

- **`sday`** *(numeric)*: Number of the day in that month (1-31)

- **`smonth`** *(numeric)*: Number of the month in that year (1-12)

- **`syear`** *(numeric)*: The year's number

- **`age`** *(numeric)*: The age of the person completing the form

- **`age2`** *(numeric)*: A binary variable (0 or 1) that says the age of the
  survey respondent is between 50 and 64 or 65 and over

- **`gender`** *(numeric)*: The gender of the survey respondent (1 - Male,
  2 -Female,
  3 - Other)

- **`gnd_age`** *(numeric)*: Divides into subgroups by age group (age2) and gender
  (gender)

- **`sp_gender`** *(numeric)*: The gender of the partner (1 - Male,
  2 - Female,
  NA -Other)

- **`trans`** *(numeric)*: Binary indicator indicating whether the person is on the
  transgender spectrum (1 - On the spectrum,
  0 - Not on the spectrum)

- **`orient`** *(numeric)*: The sexual orientation of the respondent (1 – Gay,
  2 – Lesbian,
  3 – Bisexual,
  4 – Heterosexual,
  5 – Other)

- **`marit`** *(numeric)*: What is the marital status of the survey respondent
  (1 -single,
  2 - married,
  3 - publicly known,
  4 - in a relationship,
  5 - divorced/separated,
  6 - widowed,
  7 - other)

- **`partner`** *(numeric)*: Binary indicator of partnership status (1 – Partnered,
  0– Not partnered)

- **`bio_cnt`** *(numeric)*: Over the past year, how frequently did the survey respondent
  have any form of contact (face-to-face or using any means
  of communication) with their biological/primary family members?
  (1 – Never,
  2 – Once a month or less,
  3 – Several times a month,
  4 – Several times a week,
  5 – Every day)


### All of the following variables used the same response scale:

  1 – Strongly disagree,
  2 – Disagree,
  3 – Neither agree nor disagree,
  4 – Agree,
  5 – Strongly agree


- **`bio_close`** *(numeric)*: How emotionally close does the survey respondent feel to
  their biological/primary family members?

- **`bio_acc`** *(numeric)*: The survey respondent is open about their sexual
  orientation with their biological/primary family members.
  The biological/primary family members of the survey respondent
  are supportive of their sexual orientation. This value is
  the average of these two statements.

- **`bio_comm`** *(numeric)*: The survey respondent feels committed to maintaining the
  relationship with their biological/primary family members,
  and feels that their biological/primary family members are
  committed to the relationship as well. This value is
  the average of these two statements.

- **`bio_stable`** *(numeric)*: It is unlikely that the survey respondent’s relationship with
  their biological/primary family members will end in the future.
  The survey respondent’s relationship with their biological/primary
  family members is stable. This value is the average of these two
  statements.

- **`bio_neg`** *(numeric)*: The survey respondent feels that their biological/primary
  family members are demanding and burdensome to them.

- **`bio_qlt`** *(numeric)*: Overall quality of the relationship with their primary/biological
  family - summary score based on:
  bio_close, bio_acc, bio_comm, bio_stable, bio_neg

- **`bio_lgbt`** *(numeric)*: Number of LGBTQ+ biological family members

- **`bio_suprec`** *(numeric)*: Frequency of receiving emotional support from biological
  family members:(1 – Not at all,
  2 – A little,
  3 – To some extent,
  4 – A lot,
  5 – Very much)

- **`bio_supgv`** *(numeric)*: Frequency of giving emotional support to biological
  family members:(1 – Not at all,
  2 – A little,
  3 – To some extent,
  4 – A lot,
  5 – Very much)

  **`bio_close_num`** *(numeric)*: - Number of people from the survey respondent’s
  biological/primary family to whom they feel emotionally
  connected.

  The survey respondent is now asked: Who is included in the biological/primary family
  members you mentioned in the previous question as being emotionally close to you?

- **`bio_close_child`** *(numeric)*: Binary indicator for whether the survey respondent
  identified their child as one of the biological/primary
  family members to whom they feel emotionally connected
  (1 – Yes,
  0 – No).

- **`bio_close_sib`** *(numeric)*: Binary indicator for whether the survey respondent
  identified their brother/sister as one of the biological/primary
  family members to whom they feel emotionally connected (1 – Yes,
  0 – No).

- **`bio_close_mum`** *(numeric)*: Binary indicator for whether the survey respondent
  identified their mum as one of the biological/primary family
  members to whom they feel emotionally connected (1 – Yes,
  0 – No).

- **`bio_close_dad`** *(numeric)*: Binary indicator for whether the survey respondent
  identified their dad as one of the biological/primary family members
  to whom they feel emotionally connected (1 – Yes,
  0 – No).

- **`bio_close_niece`** *(numeric)*: Binary indicator for whether the survey respondent
  identified their niece/nephew as one of the biological/primary
  family members to whom they feel emotionally connected (1 – Yes,
  0 – No).

- **`bio_close_grandchild`** *(numeric)*: Binary indicator for whether the survey respondent
  identified their grandchild as one of the biological/primary
  family members to whom they feel emotionally connected
  (1 – Yes,
  0 – No).

- **`bio_close_other`** *(numeric)*: Binary indicator for whether the survey respondent
  identified their child as one of the biological/primary
  family members to whom they feel emotionally connected
  (1 – Yes,
  0 – No).

- **`lost_mum`** *(numeric)*: Has the survey respondent’s relationship with their mum
  been harmed or broken due to their sexual orientation?
  (1 – The relationship was not harmed,
  2 – The relationship was harmed but they are still in contact,
  3 – They are no longer in contact,
  NA – Not applicable)

- **`lost_dad`** *(numeric)*: Has the survey respondent’s relationship with their dad
  been harmed or broken due to their sexual orientation?
  (1 – The relationship was not harmed,
  2 – The relationship was harmed but they are still in contact,
  3 – They are no longer in contact,
  NA – Not applicable)

- **`lost_child`** *(numeric)*: Has the survey respondent’s relationship with their child/children
  been harmed or broken due to their sexual orientation?
  (1 – The relationship was not harmed,
  2 – The relationship was harmed but they are still in contact,
  3 – They are no longer in contact,
  NA – Not applicable)

- **`lost_sib`** *(numeric)*: Has the survey respondent’s relationship with their brother/sister
  been harmed or broken due to their sexual orientation?
  (1 – The relationship was not harmed,
  2 – The relationship was harmed but they are still in contact,
  3 – They are no longer in contact,
  NA – Not applicable)

- **`lost_other`** *(numeric)*: Has the survey respondent’s relationship with other of that options
  been harmed or broken due to their sexual orientation?
  (1 – The relationship was not harmed,
  2 – The relationship was harmed but they are still in contact,
  3 – They are no longer in contact,
  NA – Not applicable)

- **`choice_partner`** *(numeric)*: Binary indicator representing whether the survey
  respondent defines their partner as chosen family
  (1 – Yes,
  0 – No)

- **`choice_friend`** *(numeric)*: Binary indicator representing whether the survey
  respondent defines one or some of their friends as chosen family
  (1 – Yes,
  0 – No)

- **`choice_neighbor`** *(numeric)*: Binary indicator representing whether the survey
  respondent defines their neighbor as chosen family
  (1 – Yes,
  0 – No)

- **`choice_ex`** *(numeric)*: Binary indicator representing whether the survey respondent
  defines their ex as chosen family (1 – Yes,
  0 – No)

- **`choice_colleague`** *(numeric)*: Binary indicator representing whether the survey respondent
  defines their colleague as chosen family (1 –Yes,
  0 – No)

- **`choice_fampar`** *(numeric)*: Binary indicator representing whether the survey respondent
  defines their partner's family as chosen family (1 – Yes,
  0 – No)

- **`choice_famex`** *(numeric)*: Binary indicator representing whether the survey respondent
  defines their ex's family as chosen family (1 – Yes,
  0 – No)

- **`choice_coparent`** *(numeric)*: Binary indicator representing whether the survey
  respondent defines their co-parent as chosen family (1 – Yes,
  0 – No)

- **`choice_other`** *(numeric)*: Binary indicator specifying whether there is someone not mentioned
  elsewhere in the survey whom the respondent defines as chosen family
  (1 – Yes,
  0 – No)

- **`choice_none`** *(numeric)*: Binary indicator specifying whether the survey respondent has no
  chosen family (1 – Yes,
  0 – No)

  For the following statements, only those who indicated earlier that they have a partner
  answered: (1 - Strongly disagree,
  2 - Disagree,
  3 - Neither agree nor disagree,
  4 - Agree,
  5 - Strongly agree):

- **`sp_close`** *(numeric)*: I feel emotionally close to my partner.

- **`sp_neg`** *(numeric)*: My partner is demanding and burdensome to me

- **`sp_acc`** *(numeric)*: Average of the ratings of the following two statements:
  I am open about my sexual orientation with my partner.
  My partner is supportive of my sexual orientation.

- **`sp_comm`** *(numeric)*: Average of the ratings of the following two statements:
  I feel committed to maintaining the relationship with my partner.
  My partner is committed to our relationship.

- **`sp_stable`** *(numeric)*: Average of the ratings of the following two statements:
  It is unlikely that my relationship with my partner will end
  in the future.
  My relationship with my partner is stable.

- **`sp_qlt`** *(numeric)*: Overall quality of the relationship with their partner -
  summary score based on:
  sp_close, sp_acc, sp_comm, sp_stable, sp_neg

- **`sp_suprec`** *(numeric)*: How often does the survey respondent receive emotional support
  from their partner? (1 – Not at all,
  2 – A little,
  3 – Somewhat,
  4 – A lot,
  5 - Very much)

- **`sp_supgv`** *(numeric)*: How much emotional support does the survey respondent
  give to their partner? (1 – Not at all,
  2 – A little,
  3 – Somewhat,
  4 – A lot,
  5 - Very much)

- **`choice_num`** *(numeric)*: Number of people the survey respondent defines as chosen family

- **`choice_cnt`** *(numeric)*: Over the past year, how frequently did the survey
  respondent have any form of contact (face-to-face or using
  any means of communication) with their family of choice members?
  (1 – Never,
  2 – Once a month or less,
  3 – Several times a month,
  4 – Several times a week,
  5 – Every day)

- **`choice_lgbt`** *(numeric)*: Number of LGBTQ+ family of choice members

- **`choice_suprec`** *(numeric)*: Frequency of receiving emotional support from family of
  choice members:
  (1 – Not at all,
  2 – A little,
  3 – To some extent,
  4 – A lot,
  5 – Very much)

- **`choice_supgv`** *(numeric)*: Frequency of giving emotional support to family of choice
  members:
  (1 – Not at all,
  2 – A little,
  3 – To some extent,
  4 – A lot,
  5 – Very much)

- **`choice_num_nopartner`** *(numeric)*: Number of family of choice members without the partner.


### For the following 5 statements:

  1 - Strongly disagree,
  2 - Disagree,
  3 - Neither agree nor disagree,
  4 - Agree,
  5 - Strongly agree

- **`choice_close`** *(numeric)*: The survey respondent feels close to their family of choice.

- **`choice_neg`** *(numeric)*: The survey respondent feels that their family of choice are
  demanding and burdensome

- **`choice_acc`** *(numeric)*: Average of the ratings of the following two statements:
  The survey respondent feels open about their sexual
  orientation with their family of choice.
  The survey respondent's family of choice supports their sexual
  orientation.

- **`choice_comm`** *(numeric)*: Average of the ratings of the following two statements:
  The survey respondent feels committed to maintaining
  the relationship with their family of choice.
  The survey respondent's family of choice members are committed
  to their relationship with the respondent.

- **`choice_stable`** *(numeric)*: Average of the ratings of the following two statements:
  It is unlikely that the survey respondent's relationship
  with their family of choice will end in the future.
  The survey respondent's relationship with their family of
  choice is stable.

- **`choice_qlt`** *(numeric)*: Overall quality of the relationship with their
  primary/biological family - summary score based on:
  choice_close, choice_acc, choice_comm, choice_stable, choice_neg

- **`friends_num`** *(numeric)*: The number of friends the survey respondent has who are
  not considered family of choice

- **`friends_nochoice_num`** *(numeric)*: The number of friends for those who indicated they do not
  have a family of choice, and for those who indicated that
  only their partner is considered family of choice

- **`org_lgbt`** *(numeric)*: How often did the survey respondent participate, if at
  all, in a community organization or group intended for LGBTQ+
  people in the past year?
  (NA - Not applicable, I am not aware of any such organizations or groups,
  1 - Never,
  2 - Several times a year, 3 - Several times a month,
  4 - Several times a week,
  5 - Every day)

- **`org_gen`** *(numeric)*: How often did the survey respondent participate, if at
  all, in a community organization or group not specifically
  intended for LGBTQ+ people in the past year?
  (NA - Not applicable, I am not aware of any such organizations or groups,
  1 - Never,
  2 - Several times a year,
  3 - Several times a month,
  4 - Several times a week,
  5 - Every day)


### For the following 5 statements in the past 2 weeks:

  1 - Never,
  2 - Some of the time,
  3 - Less than half the time,
  4 - More than half the time,
  5 - Most of the time,
  6 - All the time

- **`qol_1`** *(numeric)*: The survey respondent felt cheerful and in a good mood

- **`qol_2`** *(numeric)*: The survey respondent felt calm

- **`qol_3`** *(numeric)*: The survey respondent felt active and energetic

- **`qol_4`** *(numeric)*: The survey respondent woke up feeling refreshed and
  rested

- **`qol_5`** *(numeric)*: The survey respondent's daily life is full of things that
  interest them

- **`qol`** *(numeric)*: Average of the last 5 statements (about quality of life)

- **`lifesat`** *(numeric)*: How satisfied is the survey respondent with their life on
  a scale from 0 to 10? (0 - Not at all satisfied,
  10 - Completely satisfied)

  For the following 8 statements, the survey respondent was asked to indicate how much they
  felt the following over the past week using the following scale:
  (1 - Not at all or rarely,
  2 - Some or a small part of the time,
  3 - Occasionally or a moderate amount of the time,
  4 - Most or all of the time)

- **`cesd_1`** *(numeric)*: The survey respondent felt depressed

- **`cesd_2`** *(numeric)*: The survey respondent felt that everything they did took
  effort

- **`cesd_3`** *(numeric)*: The survey respondent's sleep was restless

- **`cesd_4`** *(numeric)*: The survey respondent felt happy

- **`cesd_5`** *(numeric)*: The survey respondent felt lonely

- **`cesd_6`** *(numeric)*: The survey respondent enjoyed life

- **`cesd_7`** *(numeric)*: The survey respondent felt sad

- **`cesd_8`** *(numeric)*: The survey respondent was unable to motivate themselves to
  do things

- **`cesd`** *(numeric)*: Depression score according to the CESD-8 scale (The last 8 QS)


### For the following 5 statements:

0 - Disagree, 1 - Agree

- **`gai_1`** *(numeric)*: The survey respondent was worried most of the time

- **`gai_2`** *(numeric)*: The survey respondent was very bothered by small things.

- **`gai_3`** *(numeric)*: The survey respondent considers themselves a worried person

- **`gai_4`** *(numeric)*: The survey respondent often feels nervous

- **`gai_5`** *(numeric)*: Most of the time, the survey respondent's thoughts make them
  feel nervous

- **`gai`** *(numeric)*: Based on the responses to the last 5 statements, the GAI
  (Geriatric Anxiety Inventory)  anxiety scale score was
  calculated for the survey respondent. The GAI scale measures
  the level of anxiety symptoms  in individuals based on their
  answers to specific statements


### For the following 3 statements:

  1 - Rarely or never,
  2 - Sometimes,
  3 - Often

- **`lon_1`** *(numeric)*: The survey respondent feels a lack of social connections

- **`lon_2`** *(numeric)*: The survey respondent feels disconnected or out of touch

- **`lon_3`** *(numeric)*: The survey respondent feels isolated from others

- **`lon`** *(numeric)*: The depression score based on the responses to the last 3 statements
  is calculated according to the UCLA 3-Item Loneliness Scale

- **`closet`** *(numeric)*: The survey respondent chooses to live their life out of the closet:
  1 - Yes, all or most people who know them are aware of their
  gender/sexual identity,
  2 - Partially, only some people who know them are aware of
  their gender/sexual identity,
  3 - Hardly, very few people are aware of their gender/sexual
  identity,
  4 - Not at all, no one except themselves is aware of their
  gender/sexual identity

- **`out2`** *(numeric)*: Binary indicator denoting (0 - In the closet,
  1 - Out of the closet)

- **`outcloset`** *(numeric)*: For respondents who answered that they are out of the closet –
  the amount of time they have been out:
  1 - Less than 1 year,
  2 - 1-2 years,
  3 - 3-5 years,
  4 - 5-10 years,
  5 - More than 10 years


### For the following 7 statements:

  1 - Strongly disagree,
  2 - Disagree,
  3 - Neither disagree nor agree,
  4 - Agree,
  5 - Strongly agree

- **`int_homophobia_1`** *(numeric)*: The survey respondent has a positive attitude towards
  their sexual orientation

- **`int_homophobia_2`** *(numeric)*: The survey respondent feels uncomfortable around people
  who are very openly public about their sexual orientations

- **`int_homophobia_3`** *(numeric)*: The survey respondent sometimes feels shame about their
  sexual orientation

- **`int_homophobia_4`** *(numeric)*: The survey respondent is concerned about what others
  think about their sexual orientation

- **`int_homophobia_5`** *(numeric)*: The survey respondent feels proud of their sexual
  orientation

- **`int_homophobia_6`** *(numeric)*: The survey respondent says they wish they were not of
  their sexual orientation

- **`int_homophobia_7`** *(numeric)*: Being open about the survey respondent's sexual
  orientation helps them express a natural part of their sexual identity

- **`int_homophobia`** *(numeric)*: Weighted score based on the last 7 questions for the
  internalized homophobia scale

  The following 5 statements relate to how people feel about aging and things that happen as
  people get older. For each of the following statements:
  (1 - Strongly disagree,
  2 - Disagree,
  3 - Neither disagree nor agree,
  4 - Agree,
  5 - Strongly agree)

- **`spa_1`** *(numeric)*: Things continue to get worse for the survey respondent as
  they age

- **`spa_2`** *(numeric)*: The survey respondent has the same level of energy as
  they did in the past year

- **`spa_3`** *(numeric)*: As the survey respondent ages, they feel more useless

- **`spa_4`** *(numeric)*: The survey respondent is as happy now as they were when
  they were younger

- **`spa_5`** *(numeric)*: As the survey respondent gets older, things are better
  than they thought they would be

- **`spa`** *(numeric)*: The survey respondent's self-perception of age
  based on the average of the last 5 statements

- **`subage_raw`** *(numeric)*: The age the survey respondent feels most of the time

- **`subage`** *(numeric)*: The ratio between chronological age and subjective age is
  calculated as (chronological age - subjective age) divided
  by chronological age. The ratio is positive if the subjective
  age is greater than the chronological age, and negative
  if it is less


### For the following 3 statements:

  1 - Never,
  2 - Rarely,
  3 - Sometimes,
  4 - Often,
  5 - Very often

- **`discr_age`** *(numeric)*: How often during the past year has the survey respondent
  experienced prejudice or unfair treatment because of their age?


- **`discr_lgbt`** *(numeric)*: How often during the past year has the survey respondent
  experienced prejudice or unfair treatment because of their
  sexual orientation?

- **`discr_sex`** *(numeric)*: How often during the past year has the survey respondent
  experienced prejudice or unfair treatment because of their gender?

- **`discr_age2`** *(numeric)*: Binary indicator denoting whether the survey respondent
  experienced discrimination or unfair treatment because
  of their age (0 - No,
  1 - Yes)

- **`discr_lgbt2`** *(numeric)*: Binary indicator denoting whether the survey respondent
  experienced discrimination or unfair treatment because of
  their sexual orientation (0 - No,
  1 - Yes)

- **`discr_sex2`** *(numeric)*: Binary indicator denoting whether the survey respondent
  experienced discrimination or unfair treatment because of
  their gender (0 - No,
  1 - Yes).

- **`child2`** *(numeric)*: Binary indicator denoting whether the survey respondent
  has children (0 - No,
  1 - Yes)

- **`nchild`** *(numeric)*: Number of children the survey respondent has (0 if none)

- **`liv_alone`** *(numeric)*: Binary indicator denoting whether the survey respondent
  lives alone (0 - No,
  1 - Yes)

- **`liv_partner`** *(numeric)*: Binary indicator denoting whether the survey respondent
  lives with his/her partner (0 - No,
  1 - Yes)

- **`liv_child`** *(numeric)*: Binary indicator denoting whether the survey respondent
  lives with his/her child/children (0 - No,
  1 - Yes)

- **`edu`** *(numeric)*: Academic level of the survey respondent
  (0 - No diploma,
  1 - Completion certificate of elementary or middle school,
  2 - Completion certificate of high school other than
  matriculation certificate,
  3 - Matriculation certificate,
  4 - Completion certificate of post-secondary school other
  than academic degree (such as teaching certificate, practical
  engineer, technician),
  5 - First academic degree or equivalent,
  6 - Second academic degree or equivalent including MD,
  7 - Third academic degree or equivalent,
  8 - Other)

- **`edu2`** *(numeric)*: Binary indicator denoting whether the survey respondent has
  higher education (0 - No,
  1 - Yes)

- **`fdistress`** *(numeric)*: When the survey respondent thinks about the total monthly income
  of their household, they feel their household manages financially:
  1 - With great difficulty,
  2 - With some difficulty,
  3 - Quite easily,
  4 - Easily

- **`emp`** *(numeric)*: The current employment status of the survey respondent is:
  1 - Retired,
  2 - Employee / Self-employed,
  3 - Devotes time to caring for family and/or unpaid household work,
  4 - Other

- **`emp2`** *(numeric)*: Binary indicator denoting whether the survey respondent
  is employed or not (0 - Not employed,
  1 - Employed)

- **`chronic2`** *(numeric)*: Binary indicator denoting whether the survey respondent
  has any chronic illnesses (0 - No,
  1 - Yes)

- **`chronic`** *(numeric)*: Number of chronic illnesses the survey respondent has

- **`chronic_hypertension`** *(numeric)*: Binary indicator denoting whether the survey respondent
  has hypertension (0 - No,
  1 - Yes)

- **`chronic_cholesterol`** *(numeric)*: Binary indicator denoting whether the survey respondent
  has high cholesterol (0 - No,
  1 - Yes)

- **`chronic_heart`** *(numeric)*: Binary indicator denoting whether the survey respondent
  has heart disease (0 - No,
  1 - Yes)

- **`chronic_heartattack`** *(numeric)*: Binary indicator denoting whether the survey respondent
  has experienced a heart attack (0 - No,
  1 - Yes)

- **`chronic_stroke`** *(numeric)*: Binary indicator denoting whether the survey respondent
  has experienced a stroke (0 - No,
  1 - Yes)

- **`chronic_obesity`** *(numeric)*: Binary indicator denoting whether the survey respondent
  suffers from obesity (0 - No,
  1 - Yes).

- **`chronic_kindey`** *(numeric)*: Binary indicator denoting whether the survey respondent
  has been diagnosed with any chronic kidney disease
  (0 - No,
  1 - Yes)

- **`chronic_eyes`** *(numeric)*: Binary indicator denoting whether the survey respondent
  has been diagnosed with any chronic eye disease
  (0 - No,
  1 - Yes)

- **`chronic_diabetes`** *(numeric)*: Binary indicator denoting whether the survey respondent
  has been diagnosed with diabetes (0 - No,
  1 - Yes)

- **`chronic_HIV`** *(numeric)*: Binary indicator denoting whether the survey respondent
  has been diagnosed with HIV (0 - No,
  1 - Yes)

- **`chronic_other`** *(numeric)*: Binary indicator denoting whether the survey respondent
  has been diagnosed with another chronic illness not specified
  here (0 - No,
  1 - Yes)

- **`sph`** *(numeric)*: Self-rated health of the survey respondent:
  1 - Poor,
  2 - Not so good,
  3 - Good,
  4 - Very good,
  5 - Excellent

- **`relig`** *(numeric)*: The survey respondent considers themselves as:
  1 - Haredi (Ultra-Orthodox),
  2 - Religious,
  3 - Traditional-Religious,
  4 - Traditional but not very religious,
  5 - Secular, not religious

- **`loc`** *(numeric)*: The survey respondent currently resides in:
  1 – Jerusalem and surrounding areas
  2 – Northern Israel (including Galilee, Golan Heights)
  3 – Haifa, Krayot, and surrounding areas
  4 – The Sharon region
  5 – Emek Hefer
  6 – Northern Coastal Plain
  7 – The city of Tel Aviv–Yafo
  8 – Greater Tel Aviv area (excluding Tel Aviv–Yafo)
  9 – The Shephelah and Southern Coastal Plain
  10 – Be’er Sheva, the Negev, and Southern Israel
  11 – Judea and Samaria (West Bank)
  12 – Currently residing abroad
  13 – Other
