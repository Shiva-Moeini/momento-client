<script lang="ts" setup>

</script>

<template>
  <VRow>
    <VCol cols="12">
      <VCard title="Timelines"><VCardText>
          
          <VForm class="mt-6">
            <VRow>
              <VCol
                md="6"
                cols="12"
              >
                <VTextField
                  placeholder="My Career Journey"
                  label="Timeline Title"
                />
              </VCol>
              <VCol
                cols="12"
                md="6"
              >
                <VTextField
                  label="Storyline"
                  placeholder="Add some details, 'Key moments in my career'"
                />
              </VCol>


              <VCol
                cols="12"
                md="6"
              >
                <VTextField
                  label="Creation Date"
                  placeholder="MM/DD/YYYY"
                />
              </VCol>

              
              <VCol
                cols="12"
                md="6"
              >
                <v-file-input label="File input" variant="outlined"></v-file-input>
              </VCol>

           
              <VCol
                cols="12"
                class="d-flex flex-wrap gap-4"
              >
                <VBtn>Save changes</VBtn>

                <VBtn
                  color="secondary"
                  variant="tonal"
                  type="reset"
                >
                  Reset
                </VBtn>
              </VCol>
            </VRow>
          </VForm>
        </VCardText>
      </VCard>
    </VCol>

  </VRow>
</template>
