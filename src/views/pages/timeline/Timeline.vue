<script lang="ts" setup>



//const refInputEl = ref<HTMLElement>()

// const accountDataLocal = ref(structuredClone(accountData))
// const isAccountDeactivated = ref(false)

// const resetForm = () => {
//   accountDataLocal.value = structuredClone(accountData)
//}
</script>

<template>
  <VRow>
    <VCol cols="12">
      <VCard title="Timelines">
        <!-- <VCardText class="d-flex">
          
        </VCardText> -->

        <VDivider />

        <VCardText>
          <!-- 👉 Form -->
          <VForm class="mt-6">
            <VRow>
              <VCol
                md="6"
                cols="12"
              >
                <VTextField
                  placeholder="John"
                  label="Name"
                />
              </VCol>
              <VCol
                cols="12"
                md="6"
              >
                <VTextField
                  label="Description"
                  placeholder="10001"
                />
              </VCol>


              <VCol
                cols="12"
                md="6"
              >
                <VTextField
                  label="Create"
                  placeholder="Select Country"
                />
              </VCol>

              <!-- 👉 Language -->
              <VCol
                cols="12"
                md="6"
              >
                <VTextField
                  label="Background Image"
                  placeholder="Select Language"
                  
                />
              </VCol>

              <!-- 👉 Form Actions -->
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
